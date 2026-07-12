# Toutiao Video Pipeline Updates

Official update channel for **Toutiao Video Pipeline / 头条视频流水线助手**.

This repository contains the current version manifest and verified Windows packages. It does not contain API keys, videos, thumbnails, publishing records, or local workflow data.

## Current release: 0.3.0

- Added a no-API ChatGPT workflow for titles, descriptions, tags, and cover backgrounds.
- One button copies the complete task and opens ChatGPT plus the reference-image folder.
- ChatGPT JSON can be pasted back to fill Chinese publishing metadata automatically.
- The app can locate the newest downloaded ChatGPT image.
- Generates three 1280x720 ASMR cover variants plus a 900x383 Toutiao cover.
- Retains the encoding-safe Windows installer, desktop shortcut, diagnostics, and SHA-256 update verification.

## Integrity

The app verifies each downloaded package against the SHA-256 value in `version.json`.
