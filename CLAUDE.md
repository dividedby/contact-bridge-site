# contact-bridge-site

Static marketing and privacy-policy site for Contact Bridge, the macOS contacts app in `dividedby/contact-bridge`. Plain HTML and CSS, no framework, no build step; `pnpm` is only used for Prettier.

## Commands

- Preview: `python3 -m http.server 8000` (also `.claude/launch.json`, name `site`).
- Format check (the only CI job, `.github/workflows/format.yml`): `pnpm format:check`.

## Gotchas

- `privacy.html` states how the app uses Google data. Keep it in step with the app's real behavior (scopes, backups, change log) and with `index.html`'s "How it uses your Google account" section.
- No deploy config is in the repo; the hosting target is not recorded here.

## Where things live

| What           | Where          |
| -------------- | -------------- |
| Landing page   | `index.html`   |
| Privacy policy | `privacy.html` |
| Shared styles  | `style.css`    |
