# Toutiao Video Pipeline Updates

Official update channel for **Toutiao Video Pipeline / 头条视频流水线助手**.

This public repository contains:

- the version manifest used by the app's **检查更新** button;
- verified Windows update packages;
- release notes and package integrity hashes.

It does **not** contain user API keys, downloaded videos, thumbnails, publishing records, or the local workflow database.

## Current release

Version **0.2.1**

- The installer now creates a desktop shortcut automatically.
- Startup failures now show a visible message and save a diagnostic log.
- Added a diagnostic launcher for easier troubleshooting.
- Kept GitHub update checking and SHA-256 verification.

## Integrity

The app verifies each downloaded package against the SHA-256 value in `version.json` before presenting it to the user.
