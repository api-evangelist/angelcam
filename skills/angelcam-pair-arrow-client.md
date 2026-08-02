---
name: Pair an Angelcam Arrow connector and add a camera
description: Pair an Arrow client (Angelcam Connector), scan its network, and register a discovered service as a camera.
api: openapi/angelcam-openapi-original.yml
operations: [arrow-client-pairing-request, arrow-clients-list, arrow-client-scan-network, arrow-client-services, add-arrow-service]
---

# Pair an Arrow connector

The Arrow client (open-source Angelcam Connector, github.com/angelcam/arrow-client) bridges local ONVIF/RTSP devices to the cloud. Scopes: `arrow_client_access`, `arrow_client_manage`.

## Steps
1. **Request pairing** — `arrow-client-pairing-request` (`POST /arrow-clients/`) with the client's MAC/identity.
2. **Confirm it's paired** — `arrow-clients-list` (`GET /arrow-clients/`); find the client `uuid`.
3. **Scan the local network** — `arrow-client-scan-network` (`POST /arrow-clients/{uuid}/scan-network/`) to discover cameras behind the connector.
4. **List services** — `arrow-client-services` (`GET /arrow-clients/{uuid}/services/`).
5. **Add a service** — `add-arrow-service` (`POST /arrow-clients/{uuid}/services/`) to expose a discovered device as a camera.

## Rules
- Trailing slash on every URL. Errors are JSON `{title, detail, status}`; 403 means missing scope.
