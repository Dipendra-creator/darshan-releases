# Darshan — Android releases

This repository holds only the release files of the Darshan Android app and their notes. The app's source code is kept private.

## Install

1. On your Android phone, open the [latest release](https://github.com/Dipendra-creator/darshan-releases/releases/latest).
2. Download `Darshan-<version>.apk` and open it. Android asks you to allow installing apps from your browser or files app the first time.

Each version installs over the one before and keeps your conversations, saved verses and settings. Android 7.0 or newer.

## Updates

From version 0.1.5, Darshan updates itself: **Settings → App updates**.

- The app checks this repository for a newer release. It also checks quietly now and then when it opens, and shows a dot on the Settings tab when a new version is waiting. The automatic check can be turned off.
- It downloads the new APK, checks its size and MD5, and hands it to Android's installer. Android only accepts an update signed with the same key as the installed app.
- Only the request itself reaches GitHub. Nothing from your conversations or settings is sent.

## What each release contains

- `Darshan-<version>.apk` — the signed app.
- `Darshan-<version>.apk.md5` — its MD5, which the app checks before installing.
- `Darshan-<version>.apk.sha256` — its SHA-256, for checking by hand.

Signing certificate SHA-256: `a4ab9e7d0039af1d0fa316539f0924fc4c6230598eac88e8790686e481dfc946`
