# ardinsights.com

Production static site for ARDInsights LLC, served by GitHub Pages.

- Source of truth for design: the "ARDInsights Website" Claude Design project (synced from `../design-system/`).
- Plain HTML + one stylesheet (`css/site.css`). No build step.
- Clean URLs via folder-per-page (`/assessment/index.html` → `/assessment/`).
- Custom domain: `www.ardinsights.com` (CNAME added at DNS cutover).

## Editing

Edit the HTML directly, commit, push to `main`. Pages redeploys automatically.
