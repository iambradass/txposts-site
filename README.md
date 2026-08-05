# txposts.com

Static site for TX Posts (sign post installation, DFW), hosted on Hostinger with GitHub auto-deploy: push to `main` = live.

- Local working copy: `~/Desktop/Clients/TX POST/hostinger-site/`
- Hostinger account `u345042583` (TitleEdge account), docroot `domains/txposts.com/public_html`
- `/order` is the canonical order form source (after DNS cutover from GHL). It posts client-side to the GHL inbound webhook and the n8n backup log; GHL opportunities/contacts/SMS are unaffected by hosting.
- Clean URLs are enforced by `.htaccess` (no `.html`, no trailing slashes; old `.html` links 301).
- Migration/cutover doc: `TX POST/TXPOSTS-HOSTINGER-CUTOVER-2026-08-05.md` (local).
