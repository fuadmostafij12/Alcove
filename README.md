# Alcove APK

Official **Android APK** downloads for [Alcove](https://github.com/fuadmostafij12/Alcove) — a private, offline-first expense ledger.

This repository hosts official release binaries. App source lives elsewhere.

## Download

**Latest release:** [Releases → Latest](https://github.com/fuadmostafij12/Alcove/releases/latest)

Or open the latest release and download `alcove-x.y.z.apk` from **Assets**.

## Install (Android)

1. Download the APK.
2. If prompted, allow **Install unknown apps** for your browser or Files app.
3. Open the APK → **Install**.
4. Open **Alcove**.

**Requirements:** Android 8.0+ (API 26+).

## What's in Alcove

- Offline expense / income / transfer tracking
- Accounts: cash, bank, MFS, credit
- People & IOUs (lent / borrowed / settle)
- Budgets, goals, insights & export
- Optional encrypted backup to **your** Google Drive

No account required for daily use. Your ledger stays on your device.

## Versions

| Tag | versionName | versionCode |
|---|---|---|
| `v1.0.0` | 1.0.0 | 1 |

See [Releases](https://github.com/fuadmostafij12/Alcove/releases) for notes and files.

## Update checks (for the app)

`version.json` on `main` (when added) describes the current build for in-app update prompts:

- `versionCode` / `versionName`
- `forceUpdate`
- `apkUrl` → GitHub Release asset

## Security notes

- Prefer downloading only from this GitHub repository's Releases.
- Sideloaded APKs are not Play Store updates.
- Lost Drive backup password = backup cannot be restored.
- Early builds may use a debug signing key; production releases should use a dedicated release keystore.

## Support

Issues about the **APK host** (broken link, wrong file): [Open an issue](https://github.com/fuadmostafij12/Alcove/issues).

Product / feature bugs: use the main Alcove app repository.

## License

APK distribution only. Source license follows the main Alcove repository.
