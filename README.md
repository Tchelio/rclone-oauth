# Personal rclone OAuth landing page

Minimal GitHub Pages site for the Google OAuth consent screen used with a personal [rclone](https://rclone.org/) Google Drive configuration.

This is **not** an OAuth callback endpoint, Google Drive client, public login service, or a project affiliated with the rclone maintainers.

## Google OAuth branding fields (after Pages is enabled)

- Application homepage: `https://tchelio.github.io/`
- Privacy policy: `https://tchelio.github.io/privacy.html`
- Authorized domain: `tchelio.github.io` (subject to what Google Cloud accepts)
- Application logo: leave blank (optional)

Do not store OAuth client secrets, refresh tokens, Google Drive content, or `rclone.conf` in this repository.

## Enable GitHub Pages

This is a GitHub Pages **user site**, served from the public repository `Tchelio/Tchelio.github.io`. In **Settings > Pages**, choose **Deploy from a branch**, branch `main`, folder `/docs`, and **Save**. The static site assets are inside `docs/`, but are served at the **domain root**.

The Search Console HTML verification file `docs/googlea594fff21931fc2d.html` is available at `https://tchelio.github.io/googlea594fff21931fc2d.html` once Pages finishes deploying. For a new URL-prefix property, enter `https://tchelio.github.io/` (without the old `/rclone-oauth/` path). Keep the HTML verification file in the repository.

Google's OAuth app verification may still require a **DNS-verified domain property**. A GitHub Pages URL-prefix ownership check is not a guarantee of successful OAuth branding verification. GitHub does not provide DNS control over `github.io`; if Google requires DNS verification, use a domain you control instead.
