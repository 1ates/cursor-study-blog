---
applyTo: "server/**/*.js"
description: "Backend rules for the Express + MongoDB app."
---

- Keep routes thin; put business logic in controllers/service/model layers.
- Validate request payloads before processing and reject invalid input early.
- Preserve the existing auth, validation, rate-limit, and error middleware flow.
- Keep MongoDB access in the model/service layer, not in route handlers.
- Use env variables for secrets, DB config, and external service keys.
- Return consistent API responses and never expose stack traces or sensitive data.
- Test the changed endpoint behavior and the failure cases that matter.
