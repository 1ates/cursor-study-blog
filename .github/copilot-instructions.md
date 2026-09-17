# Copilot instructions

- Keep frontend and backend work scoped to their own app folders.
- Match the current repo structure and patterns before introducing new abstractions.
- Do not hardcode secrets, URLs, or credentials; use env files.
- Keep API contracts and UI behavior aligned across client/server changes.
- Prefer the existing patterns in the repo over creating parallel implementations.
- Validate the changed behavior with the smallest relevant check before finishing.
- Never expose stack traces, tokens, or sensitive data in responses.
