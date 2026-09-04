# Changelog

## 0.0.3 — 2026-09-04

- Fixed a crash on launch: the app’s texts and icon were missing from the Android build, so the first screen could not load.
- Screen changes now use a lighter shared-axis slide, with a fade-through for the sending and finished screens, and respect the system reduced-motion setting.
- Updated Compose, AndroidX, Ktor, Coil, and Sentry to their latest releases.

## 0.0.2 — 2026-07-27

- Reworked the migration flow: clearer step-by-step wizard, per-album and per-folder selection, and a redesigned sending screen with live progress.
- Fixed transfers silently failing on Android 17, where the new local-network permission blocked the connection to the new phone.
- Failure screens now explain what went wrong — including missing local-network access — instead of showing a generic error.

## 0.0.1 — 2026-07-06

First public release.

- Send contacts, photos, videos, and files from your old Android phone to a new device running the Sleke setup wizard.
- Direct phone-to-phone transfer over Wi-Fi — nothing is uploaded to the cloud.
- Pair by scanning the QR code shown on the new phone; the connection is certificate-pinned before any data is sent.
- Requires Android 9 (Pie) or newer.
