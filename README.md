# openclaw-oauth-consent

Static homepage + privacy policy for the Google Cloud OAuth consent screen of the
personal **"My local OpenClaw"** project (Cloud project `my-local-openclaw-498709`,
number `452854601918`).

## Why this exists

Google requires an app **homepage URL** and a **privacy policy URL** before an
external OAuth app can be switched from *Testing* to *In production*. Production
status is what stops Google from expiring the app's refresh tokens every 7 days
(the failure that took down the `gog` / contacts-cleanup automation in Sept 2026).

This repo is **only** here to satisfy that requirement. It is not the OpenClaw
application and contains no code.

## Published via GitHub Pages

- Homepage:       `https://bendboaz.github.io/openclaw-oauth-consent/`
- Privacy policy: `https://bendboaz.github.io/openclaw-oauth-consent/privacy.html`

Enable at repo **Settings -> Pages -> Deploy from a branch -> `main` / `/` (root)**.

Public contact address on both pages: `bendboaz@gmail.com`.
