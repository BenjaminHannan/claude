# Claude Web Portal

A small static website that provides a Claude-style shell and attempts to embed `https://claude.ai` inside an iframe.

## Run locally

```bash
python3 -m http.server 4173
```

Then visit <http://localhost:4173>.

## Notes

- Embedding may fail because `claude.ai` can set anti-embedding security headers (`X-Frame-Options` and CSP `frame-ancestors`).
- If embedding is blocked, use the **Open Claude** button to open the official site in a new tab and sign in normally.
