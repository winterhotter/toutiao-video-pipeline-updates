# Toutiao Video Pipeline Updates

Official update channel for **Toutiao Video Pipeline / 头条视频流水线助手**.

This public repository contains the current version manifest, verified Windows update packages, release notes, and package integrity hashes. It does not contain user API keys, videos, thumbnails, publishing records, or local workflow data.

## Current release

Version **0.2.2**

- Fixed Windows CMD encoding errors that caused Chinese text to be interpreted as commands.
- Converted every BAT and PowerShell installer/launcher script to ASCII with Windows CRLF line endings.
- Kept the Chinese application interface.
- The installer creates a desktop shortcut.
- Startup failures show a visible message and save a diagnostic log.

## Integrity

The app verifies each downloaded package against the SHA-256 value in `version.json`.
