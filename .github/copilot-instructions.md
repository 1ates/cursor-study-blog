# Copilot instructions

- Keep frontend and backend work scoped to their own app folders.
- Match the current repo structure and patterns before introducing new abstractions.
- Keep client/server contracts aligned; do not break the current API or UI flow.
- Do not hardcode secrets, URLs, or credentials; use env files.
- Validate the changed behavior with the smallest relevant test or check.
- Never expose stack traces, tokens, or sensitive data in responses.
- Prefer the existing repo patterns over parallel implementations.
