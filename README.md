# ClipFlow Studio

Official Android APK releases for ClipFlow Studio. No Google Play Store is required.

## Install or update

[Download the latest APK](https://github.com/rupanpahari/clipflow-studio-updates/releases/latest/download/ClipFlow-Studio.apk)

[Release notes](https://github.com/rupanpahari/clipflow-studio-updates/releases/latest)

Install the APK over your existing ClipFlow Studio app. Do **not** uninstall or clear app data if you want to retain your projects and settings. Android asks you to approve installation and may require **Allow from this source**.

If you have an older APK without configured remote updates, install the updater-enabled release once manually. Subsequent published releases are offered automatically when you launch the app. You can also open **Settings · App Updates → Check for Updates**.

## Authenticity

- Application ID: `studio.clipflow.app.fresh`
- Signing certificate SHA-256: `d803db992f3c6d660a2532b2a3d86c3c470b330011a213cc6f23dc6a510410d2`
- Updates are downloaded over HTTPS and checked for byte size, SHA-256, package identity, newer versionCode, and signing certificate before Android's installer opens.

The updater reads [latest.json](https://github.com/rupanpahari/clipflow-studio-updates/releases/latest/download/latest.json). Release-specific APK URLs are used so metadata always identifies exact bytes.

This repository contains public releases and update metadata only. It does not contain signing keys or user project media.
