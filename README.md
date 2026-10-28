# AngelCam

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Angelcam is a cloud video-surveillance platform that connects any IP camera to the cloud — via ONVIF and the open-source Arrow connector — for live viewing, cloud recording, clip creation and sharing, two-way audio, sensors, and Remote Technical Surveillance (RTS) event notifications. The Angelcam RESTful API (HTTPS-only JSON, organised around Spaces, secured with OAuth2 or a Personal Access Token) exposes 90+ endpoints across cameras, recordings, clips, events, Arrow clients, notifications, speakers, and services.

**Areas:** Company · Video Surveillance · Camera · IP Camera · Cloud Recording · Video Streaming · IoT · ONVIF · Security · Webhook

## AngelCam on APIs.io

Everything profiled for AngelCam is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/angelcam/](https://apis.io/providers/angelcam/)** — or go straight to one of the APIs or properties below.

### APIs (29)

- [AngelCam Active Service API](https://apis.io/apis/angelcam/angelcam-active-service-api/) — Endpoints for managing your activated services and assigning them to cameras. A service must first be activated (purchased) for your account, then assigned…
- [AngelCam Angelcameras API](https://apis.io/apis/angelcam/angelcam-angelcameras-api/) — The angelcameras API from AngelCam — 1 operation(s) for angelcameras.
- [AngelCam Arrow Clients API](https://apis.io/apis/angelcam/angelcam-arrow-clients-api/) — Manage [Arrow clients](https://github.com/angelcam/arrow-client) — pair them with your account, inspect exposed services, and send commands. **Pairing:**…
- [AngelCam Audio Message API](https://apis.io/apis/angelcam/angelcam-audio-message-api/) — Endpoints for managing audio messages. Audio messages are pre-recorded audio clips that can be played through [speakers](#tag/speakers). Audio files are…
- [AngelCam Broadcasting API](https://apis.io/apis/angelcam/angelcam-broadcasting-api/) — Endpoints for managing broadcasting settings and retrieving broadcasting streams. If a camera doesn't have the Broadcasting service activated, all camera…
- [AngelCam Camera API](https://apis.io/apis/angelcam/angelcam-camera-api/) — Manage your cameras and access live streams, snapshots, and recordings. Supported codecs: H.264, H.265 (experimental), MJPEG. Live streams are limited to 10…
- [AngelCam Camera Guest API](https://apis.io/apis/angelcam/angelcam-camera-guest-api/) — You can share your camera with a guest, this means, you allow guests to view stream from your camera. There is also an option to share also recordings…
- [AngelCam Camera Stream Detection API](https://apis.io/apis/angelcam/angelcam-camera-stream-detection-api/) — Using these endpoints you can verify if there are camera streams available on specified network address. Detection is asynchronous. For this reason there is…
- [AngelCam Client API](https://apis.io/apis/angelcam/angelcam-client-api/) — Endpoints for reseller users to manage their clients. A reseller can create two types of client accounts: * **Full account** — the client has full control…
- [AngelCam Clip API](https://apis.io/apis/angelcam/angelcam-clip-api/) — A clip is a permanent, downloadable excerpt of recorded footage. Unlike a recording stream — which is a temporary playback session — a clip is processed…
- [AngelCam Event API](https://apis.io/apis/angelcam/angelcam-event-api/) — Events represent detections reported by cameras or sensors — typically motion detected by a camera or a trigger from an external sensor. Events are the…
- [AngelCam Incidents API](https://apis.io/apis/angelcam/angelcam-incidents-api/) — Endpoints for managing Real Time Security (RTS) incidents. An incident is a security event that has been detected and may require attention. Incidents are…
- [AngelCam Location API](https://apis.io/apis/angelcam/angelcam-location-api/) — Endpoints for accessing and managing locations. Locations are used to organize cameras into groups. Every camera belongs to exactly one location, and every…
- [AngelCam Order API](https://apis.io/apis/angelcam/angelcam-order-api/) — The order API from AngelCam — 3 operation(s) for order.
- [AngelCam Public Camera API](https://apis.io/apis/angelcam/angelcam-public-camera-api/) — Endpoints for browsing cameras that are publicly accessible. A camera appears here if it has the Broadcasting service active and has been marked as public —…
- [AngelCam Recording API](https://apis.io/apis/angelcam/angelcam-recording-api/) — Cloud Recording endpoints. Requires the Cloud Recording service to be active on the camera — otherwise all endpoints return 404. A camera can have multiple…
- [AngelCam Rts Messages API](https://apis.io/apis/angelcam/angelcam-rts-messages-api/) — Endpoints for managing notifications. Base object is message. We create a message when something important happens. For example, when a camera goes offline,…
- [AngelCam Rts Notification Methods API](https://apis.io/apis/angelcam/angelcam-rts-notification-methods-api/) — Manage notification methods — email and HTTP webhook. HTTP methods send a signed POST to your URL with a JSON payload on each notification. See the…
- [AngelCam Rts Notification Rules API](https://apis.io/apis/angelcam/angelcam-rts-notification-rules-api/) — Endpoints for managing notification rules. Notification rule is a rule that defines when and how we should send message to user. For example, we can create…
- [AngelCam Rts Settings API](https://apis.io/apis/angelcam/angelcam-rts-settings-api/) — Global Real Time Security (RTS) settings for your account. The main setting is `incident_ttl`, which controls how long (in [ISO 8601 duration…
- [AngelCam Sensor API](https://apis.io/apis/angelcam/angelcam-sensor-api/) — With sensor endpoints you can view, manage and connect sensors to the user account. Sensor can be bind to one particular already connected…
- [AngelCam Service API](https://apis.io/apis/angelcam/angelcam-service-api/) — A catalog of services available for purchase. Use these endpoints to discover service `code` values before activating a service via the [My…
- [AngelCam Shared Camera API](https://apis.io/apis/angelcam/angelcam-shared-camera-api/) — For access to cameras which somebody shared with you. In general everything is same as in my cameras section, see above, there is only one difference.…
- [AngelCam Shared Camera Clip API](https://apis.io/apis/angelcam/angelcam-shared-camera-clip-api/) — Recording clips on cameras shared with you. Everything works the same as [My recording clips](#tag/clip) — just replace `cameras` with `shared-cameras` in…
- [AngelCam Shared Camera Recording API](https://apis.io/apis/angelcam/angelcam-shared-camera-recording-api/) — Everything is same as in recording for my own cameras. Just replace `cameras` by `shared-cameras` in every endpoints url.
- [AngelCam Space API](https://apis.io/apis/angelcam/angelcam-space-api/) — A **space** is the organisational unit in Angelcam — it owns all resources: cameras, locations, recordings, services, and billing. Every API request…
- [AngelCam Speakers API](https://apis.io/apis/angelcam/angelcam-speakers-api/) — Manage speakers and trigger audio playback. See the [Speakers guide](/guides/speakers/) for setup instructions, including how to configure an AngelBox as a…
- [AngelCam Stream Controls API](https://apis.io/apis/angelcam/angelcam-stream-controls-api/) — You normally don't have to know the `streamer_domain` and `stream_id` path parameter, but use the generated endpoint URLs as reported by the…
- [AngelCam User API](https://apis.io/apis/angelcam/angelcam-user-api/) — The user API from AngelCam — 1 operation(s) for user.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Arazzo workflows (2)

Multi-step workflows that chain operations into a business task.

- [Angelcam — create and share a clip](https://apis.io/arazzos/angelcam/angelcam-create-and-share-clip/)
- [Angelcam — watch a live camera](https://apis.io/arazzos/angelcam/angelcam-watch-live-camera/)

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Angelcam Webhooks](https://apis.io/asyncapis/angelcam/angelcam-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [angelcam](https://apis.io/servers/angelcam/angelcam/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Angelcam Agentic Access](https://apis.io/agentic-access/angelcam/angelcam-agentic-access/)

#### Collections (29)

Postman and Open Collection request collections.

- [Angelcam Active Service API](https://apis.io/collections/angelcam/open-angelcam-active-service-api/)
- [Angelcam active-service Angelcameras API](https://apis.io/collections/angelcam/open-angelcam-angelcameras-api/)
- [Angelcam active-service Arrow Clients API](https://apis.io/collections/angelcam/open-angelcam-arrow-clients-api/)
- [Angelcam active-service Audio Message API](https://apis.io/collections/angelcam/open-angelcam-audio-message-api/)
- [Angelcam active-service Broadcasting API](https://apis.io/collections/angelcam/open-angelcam-broadcasting-api/)
- [Angelcam active-service Camera API](https://apis.io/collections/angelcam/open-angelcam-camera-api/)
- [Angelcam active-service Camera Guest API](https://apis.io/collections/angelcam/open-angelcam-camera-guest-api/)
- [Angelcam active-service Camera Stream Detection API](https://apis.io/collections/angelcam/open-angelcam-camera-stream-detection-api/)
- [Angelcam active-service Client API](https://apis.io/collections/angelcam/open-angelcam-client-api/)
- [Angelcam active-service Clip API](https://apis.io/collections/angelcam/open-angelcam-clip-api/)
- [Angelcam active-service Event API](https://apis.io/collections/angelcam/open-angelcam-event-api/)
- [Angelcam active-service Incidents API](https://apis.io/collections/angelcam/open-angelcam-incidents-api/)
- [Angelcam active-service Location API](https://apis.io/collections/angelcam/open-angelcam-location-api/)
- [Angelcam active-service Order API](https://apis.io/collections/angelcam/open-angelcam-order-api/)
- [Angelcam active-service Public Camera API](https://apis.io/collections/angelcam/open-angelcam-public-camera-api/)
- [Angelcam active-service Recording API](https://apis.io/collections/angelcam/open-angelcam-recording-api/)
- [Angelcam active-service Rts Messages API](https://apis.io/collections/angelcam/open-angelcam-rts-messages-api/)
- [Angelcam active-service Rts Notification Methods API](https://apis.io/collections/angelcam/open-angelcam-rts-notification-methods-api/)
- [Angelcam active-service Rts Notification Rules API](https://apis.io/collections/angelcam/open-angelcam-rts-notification-rules-api/)
- [Angelcam active-service Rts Settings API](https://apis.io/collections/angelcam/open-angelcam-rts-settings-api/)
- [Angelcam active-service Sensor API](https://apis.io/collections/angelcam/open-angelcam-sensor-api/)
- [Angelcam active Service API](https://apis.io/collections/angelcam/open-angelcam-service-api/)
- [Angelcam active-service Shared Camera API](https://apis.io/collections/angelcam/open-angelcam-shared-camera-api/)
- [Angelcam active-service Shared Camera Clip API](https://apis.io/collections/angelcam/open-angelcam-shared-camera-clip-api/)
- [Angelcam active-service Shared Camera Recording API](https://apis.io/collections/angelcam/open-angelcam-shared-camera-recording-api/)
- …and 4 more published on APIs.io

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Angelcam Openapi Overlay](https://apis.io/overlays/angelcam/angelcam-openapi-overlay/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Angelcam Authentication](https://apis.io/security/angelcam/angelcam-authentication/)
- [Angelcam Domain Security](https://apis.io/security/angelcam/angelcam-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Angelcam Scopes](https://apis.io/scopes/angelcam/angelcam-scopes/)

#### Rate limits (1)

Published request limits.

- [Angelcam Rate Limits](https://apis.io/rate-limits/angelcam/angelcam-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://angelcam.com)
- [Documentation](https://developers.angelcam.com/)
- [Getting started](https://developers.angelcam.com/guides/key-concepts/)
- [API reference](https://developers.angelcam.com/)
- [Support](https://help.angelcam.com)
- [Blog](https://angelcam.com/blog/)
- [Terms of service](https://angelcam.com/terms/)
- [Privacy policy](https://angelcam.com/privacy/)
- [GitHub](https://github.com/angelcam)
- [Status](https://status.angelcam.com)

## API Evangelist rating

**Kin Score 48.7** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 56.8 |
| Contract governance | 4.5 |
| Operational transparency | 55.3 |
| Developer ergonomics | 58.9 |
| Access clarity | 27.6 |

**Agent readiness 42.3** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | negotiable (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | yes |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | documented (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | paginated |
| Operation Distinctiveness | mostly |

**Regulatory alignment 34.3** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/angelcam/](https://apis.io/providers/angelcam/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for AngelCam: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/angelcam/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
