---
applyTo: "client/**/*.{js,jsx}"
description: "Frontend rules for the Vite + React app."
---

- Keep components presentation-focused; move API/data logic into `src/api`, `src/hooks`, or `src/context`.
- Follow the current `@/` alias and folder structure instead of creating new app-level patterns.
- Keep auth checks and route protection aligned with the existing app context and route constants.
- Use the shared UI conventions (`antd`, constants, i18n) instead of ad hoc styling.
- Validate user input and handle loading/error states for all async actions.
- Do not hardcode API URLs, tokens, or environment-specific values.
- Test the changed user flow, not just the component render.
