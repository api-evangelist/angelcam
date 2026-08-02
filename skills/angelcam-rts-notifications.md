---
name: Set up Angelcam RTS event notifications (webhook)
description: Create an HTTP (webhook) or email notification method and a rule that fires it on camera messages.
api: openapi/angelcam-openapi-original.yml
operations: [rts-notification-method-create, rts-notification-rule-create, rts-notifications-methods, rts-notifications-rules]
---

# Set up RTS notifications

Remote Technical Surveillance (RTS) pushes camera messages to a notification method. HTTP methods deliver signed webhooks (HMAC via `signature_private_key`) to your URL. Scopes: `notifications_methods_manage`, `notifications_rules_manage`.

## Steps
1. **Create a notification method** — `rts-notification-method-create` (`POST /rts/notifications/methods/`). For a webhook set `type: http`, `http_method`, `url`, and a `signature_private_key`; for email set `type: email`, `email`.
2. **Create a rule** — `rts-notification-rule-create` (`POST /rts/notifications/rules/`) binding a `message_type` + `allowed_cameras`/`allowed_arrow_clients` to the `notification_method` id.
3. **Verify** — `rts-notifications-methods` and `rts-notifications-rules` list what's configured.

## Rules
- Verify the HMAC signature on inbound webhooks using your `signature_private_key`.
- Trailing slash on every URL; JSON only. Respect rate limits (30/min, 1000/hour).
