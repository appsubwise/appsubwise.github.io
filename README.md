# SubWise — GitHub Pages site

Static site that hosts the SubWise privacy policy, terms, and support page. Required by App Store Connect (privacy URL is mandatory) and linked from inside the app.

## Deployed

Hosted as GitHub Pages **user site** at `appsubwise/appsubwise.github.io` (root).

Live URLs:
- `https://appsubwise.github.io/`
- `https://appsubwise.github.io/privacy.html`
- `https://appsubwise.github.io/terms.html`
- `https://appsubwise.github.io/support.html`

Push to `main` to deploy. `AppURLs.base` in `SubWise/Services/DiagnosticsInfo.swift` is the single source of truth — change it if you move to a custom domain.

## Custom domain later

If you register a real domain (e.g. subwise.app), add a `CNAME` file to this folder with the domain, configure DNS, and update `AppURLs.base`.
