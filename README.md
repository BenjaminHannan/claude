# Claude Access Portal

A simple static launcher page for opening the official Claude web app (`https://claude.ai`).

## Why no embed?

Claude blocks third-party iframe embedding using browser security headers (for example CSP `frame-ancestors` and/or `X-Frame-Options`).
That means a custom website cannot reliably show the real Claude UI inside an `<iframe>`.

## Run locally

```bash
python3 -m http.server 4173
```

Then visit <http://localhost:4173> and use one of the launch buttons.

## Important

- This project does **not** bypass school/workplace restrictions.
- If `https://claude.ai` is blocked on a managed network/device, ask your administrator for approved access.
