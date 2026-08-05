# Recovery Hub — Releases

Public download host for **Recovery Hub** (Windows) and **Connect Recovery** (Android).

This repository contains installers and a `release.json` manifest. **No source code lives here** —
the application source is private.

## Downloads

Grab the newest build from the [Releases page](../../releases/latest):

| File | For |
|---|---|
| `RecoveryHub-<version>-Setup.msi` | Windows office computer |
| `ConnectRecovery-<version>-release.apk` | Collectors' Android phones |

## Automatic updates

Both applications check this repository themselves — **Settings → Updates** in either app. Every
download is verified against the SHA-256 published in `release.json` before it is installed; a
mismatch is deleted rather than installed.

Nobody needs to be sent a download link.
