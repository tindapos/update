# TindaPOS Update Server

This repository serves as the update distribution channel for TindaPOS Android app.

## Files
- `version.json` — latest version manifest (fetched by the app on startup)
- Releases — signed APK files attached to each GitHub Release

## How it works
The TindaPOS app checks `version.json` on every launch. If a newer `versionCode` is found, it shows an update prompt and downloads the APK from the release assets.
