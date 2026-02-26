---
paths:
  - "src/**/*.{ts,tsx}"
---

# Landing Page Security

- No user input forms beyond contact — validate and sanitize if added
- No API routes — static landing only
- CSP headers via Next.js config if external resources are loaded
- No secrets in client-side code
