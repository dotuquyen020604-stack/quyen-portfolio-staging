# Quyen Portfolio — Claude Code Instructions

## Project
This is Quyen Pham's personal portfolio website (`index.html`).

## Deployment Rules — ALWAYS FOLLOW THIS ORDER

### Step 1 — Push to STAGING first
```
git add index.html
git commit -m "<describe the change>"
git push origin-staging main
```
Wait and confirm staging looks good before continuing.

### Step 2 — Push to LIVE only after staging is confirmed
```
git push origin main
```

### Step 3 — Always end every session by showing both URLs
After any push, ALWAYS display:
- 🧪 **Staging:** https://dotuquyen020604-stack.github.io/quyen-portfolio-staging/
- 🟢 **Live:** https://dotuquyen020604-stack.github.io/quyen-portfolio/

## Git Remotes
- `origin` → live site: https://github.com/dotuquyen020604-stack/quyen-portfolio.git
- `origin-staging` → staging site: https://github.com/dotuquyen020604-stack/quyen-portfolio-staging.git

## Workflow Summary
Edit → stage → commit → push staging → check → push live → show URLs

## Project Files
- `index.html` — the entire website (HTML + CSS + JS in one file)

## Notes
- Never push directly to live without staging first
- Always give both URLs at the end, even if only staging was updated
- The user is non-technical — keep explanations simple and clear
