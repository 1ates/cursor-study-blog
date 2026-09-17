---
applyTo: "client/**/*.{js,jsx}"
description: "Frontend rules for the Vite + React app."
---

- Keep components presentation-focused; move API/data logic into `src/api`, `src/hooks`, or `src/context`.
- Follow the current `@/` alias and repo folder structure instead of adding new app-level patterns.
- Keep auth checks and route protection aligned with the existing app context and route constants.
- Use the shared UI conventions (`antd`, constants, i18n) instead of ad hoc styling.
- Validate user input and handle loading/error states for async actions.
- Do not hardcode API URLs, tokens, or environment-specific values.
- Test the changed user flow and the failure path, not only the happy path.
- Sanitize or safely render user-supplied content and avoid unsafe HTML injection.
