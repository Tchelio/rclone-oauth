# Personal rclone OAuth landing page

Minimal GitHub Pages site for the Google OAuth consent screen used with a personal [rclone](https://rclone.org/) Google Drive configuration.

This is **not** an OAuth callback endpoint, Google Drive client, public login service, or a project affiliated with the rclone maintainers.

## Google OAuth branding fields (after Pages is enabled)

- Application homepage: `https://tchelio.github.io/rclone-oauth/`
- Privacy policy: `https://tchelio.github.io/rclone-oauth/privacy.html`
- Authorized domain: `tchelio.github.io` (subject to what Google Cloud accepts)
- Application logo: leave blank (optional)

Do not store OAuth client secrets, refresh tokens, Google Drive content, or `rclone.conf` in this repository.

## Enable GitHub Pages

When ready, make the repository public (GitHub Free), then in **Settings > Pages**, choose **Deploy from a branch**, branch `main`, folder `/docs`, and **Save**. Wait for both links above to return the actual pages before entering them in Google Cloud.
