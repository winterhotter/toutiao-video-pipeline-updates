# Toutiao Video Pipeline Updates

Official update channel for **Toutiao Video Pipeline / 头条视频流水线助手**.

This public repository contains:

- the version manifest used by the app's **检查更新** button;
- verified Windows update packages;
- release notes and package integrity hashes.

It does **not** contain user API keys, downloaded videos, thumbnails, publishing records, or the local workflow database.

## Current release

Version **0.2.0**

- Added GitHub update checking.
- Added release notes and version comparison.
- Added SHA-256 package verification.
- Updates download only after user confirmation.

## Integrity

The app verifies each downloaded package against the SHA-256 value in `version.json` before presenting it to the user.
