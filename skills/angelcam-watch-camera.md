---
name: Watch an Angelcam live camera stream
description: List your cameras and open a live stream for one of them.
api: openapi/angelcam-openapi-original.yml
operations: [my-cameras-list, my-cameras-detail]
---

# Watch a live camera stream

Base URL `https://api.angelcam.com/v1` — every URL needs a trailing slash. Authenticate with `Authorization: PersonalAccessToken {token}` (scope `camera_access`). Requests run in your default space unless you set `X-Space-Id`.

## Steps
1. **List cameras** — `my-cameras-list` (`GET /cameras/`). Page with `limit`/`offset`; read `results`, `count`, `next`. Pick the target `camera_id`.
2. **Get the camera** — `my-cameras-detail` (`GET /cameras/{camera_id}/`). The response carries the live-stream URLs (H.264/H.265/MJPEG). Live streams are limited to 10 concurrent consumers per camera — use broadcasting for higher concurrency.
3. Open the returned stream URL in your player.

## Rules
- Rate limits: 30/min, 1000/hour → back off on HTTP 429 (wait time is in the `detail` field).
- Errors are JSON `{title, detail, status}`. 403 means your token is missing the required scope.
