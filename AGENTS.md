# Agent instructions

## Cursor Cloud specific instructions

This repo is a **single-file static site** (`index.html`). No `npm install` or build step.

### Run locally

From this directory:

```bash
python3 -m http.server 8083
```

Open http://127.0.0.1:8083/

### Lint / test

None defined in-repo. Edit `index.html` and verify in a browser.

### Maintenance

See `README.md` for updating download links and version metadata in `index.html`.

### Related repos in the same workspace

- `../audit-report-viewer` — renders UX audit JSON (demo: http://127.0.0.1:8082/ → 查看示例报告)
- `../ai-design-trial-qa` — AI design trial FAQ (http://127.0.0.1:8081/)
