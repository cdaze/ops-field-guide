# ops-field-guide

Claude + Obsidian Operations Field Guide — 3PL & Operations Management Edition.

Hosted via Netlify. Auto-deploys on every push to `main`.

## Update workflow

```bash
# After downloading updated index.html from Claude:
git add index.html
git commit -m "Update: <brief description> vX.X"
git push
# Netlify deploys in ~15 seconds. Same URL, new content.
```

## Files

| File | Purpose |
|------|---------|
| `index.html` | The guide — edit this |
| `netlify.toml` | Netlify build + header config |

## Versions

| Version | Date | Changes |
|---------|------|---------|
| v1.3 | 2026-05-26 | Added Claude Design (research preview) |
| v1.2 | 2026-05-26 | Full macOS + Windows 11 install sections |
| v1.1 | 2026-05-26 | Added Obsidian setup guide |
| v1.0 | 2026-05-26 | Initial release — models, agents, skills, TELOS |
