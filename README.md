# WOD Clock — Legal & Landing

Public site for the WOD Clock mobile app, served via GitHub Pages.

- `index.html` — landing page
- `privacy.html` — privacy policy (store submission URL)
- `terms.html` — terms of use (store submission URL)
- `style.css` — shared styles (matches the app's dark minimalist theme)
- `icon.png` — app icon (add before release)

> This repository is **public**. No secrets, no internal docs — only the site content.

## Publishing

GitHub Pages → Settings → Pages → Deploy from branch `main`, root `/`. The site is plain static HTML — no build step.

## Store URLs

Once published, use these as the app-store metadata links:

- Privacy Policy: `https://tonixhaker.github.io/wod-timer-legal/privacy.html`
- Terms of Use: `https://tonixhaker.github.io/wod-timer-legal/terms.html`

Replace the placeholder store badges in `index.html` with real App Store / Google Play URLs at release.
