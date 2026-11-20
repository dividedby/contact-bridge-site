# contact-bridge-site

The landing page and privacy policy for [Contact Bridge](https://github.com/dividedby/contact-bridge), a macOS app that syncs iCloud Contacts to Google Contacts.

Plain HTML and CSS with no framework and no build step. `pnpm` is only used for Prettier.

## Preview

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Files

- `index.html`: landing page.
- `privacy.html`: privacy policy. Keep it in step with the app's real behaviour and with the "How it uses your Google account" section of `index.html`.
- `style.css`: shared styles.

## Checks

`pnpm format:check` (Prettier); `pnpm format` fixes. CI runs the check.

## Licence

MIT. See [`LICENSE`](./LICENSE).
