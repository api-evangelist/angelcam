---
name: Create and share an Angelcam recording clip
description: Find a recording, inspect its timeline, create a clip, and share it via email.
api: openapi/angelcam-openapi-original.yml
operations: [my-cameras-recordings-list, my-cameras-recording-timeline, my-cameras-clips-create, my-cameras-clips-share]
---

# Create and share a clip

Requires the Cloud Recording service active on the camera (otherwise recording endpoints return 404). Scopes: `recording_access`, `recording_clips_create`, `recording_clips_share`.

## Steps
1. **List recordings** — `my-cameras-recordings-list` (`GET /cameras/{camera_id}/recordings/`). Choose a `recording_id`.
2. **Inspect the timeline** — `my-cameras-recording-timeline` (`GET /recording/{recording_id}/timeline/`). Segments are continuous recorded blocks; max range per request is 24 hours. Use ISO 8601 timestamps (UTC).
3. **Create the clip** — `my-cameras-clips-create` (`POST /cameras/{camera_id}/clips/`) with the start/end within an available segment.
4. **Share it** — `my-cameras-clips-share` (`POST /cameras/{camera_id}/clips/{clip_id}/share/`) with the recipient email.

## Rules
- Trailing slash on every URL; JSON only.
- Durations use ISO 8601 (e.g. `PT2M`). Watch rate limits (30/min, 1000/hour).
