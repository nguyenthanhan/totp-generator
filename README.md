# TOTP Generator

A simple client-side React app for generating 6-digit TOTP tokens from Base32 secrets.

## Features

- RFC 6238 TOTP with HMAC-SHA1
- 6-digit tokens
- Base32 secrets with spaces and lowercase letters accepted
- Automatic token refresh at the 30-second TOTP boundary
- Copy token by clicking the token or the copy button
- Light mode by default with dark mode toggle
- No backend, no API calls, no secret storage

## Local Development

```bash
npm install
npm run dev
```

## Production Build

```bash
npm run build
npm run preview
```

Deploy the generated `dist/` directory to any static hosting provider.
