# Session Craft 0.1.6

**Session Craft Community Edition is free to download and use.** This release keeps the core desktop workflow available without a subscription requirement.

## What stands out in this release

- Moved multi-stem playback onto the shared realtime audio engine while preserving speed, pitch shift, loop bounds, seek state, per-stem mute, solo, gain, and device-rate-correct timing.
- Six-stem separation now uses the shared universal separator and model locator, with explicit decode, verification, model-loading, inference, and output-finalization progress.
- The bundled HTDemucs model is fetched, staged, and SHA-verified through the revision-pinned model-asset catalog with source provenance carried into the package.
- Hardened native packaging and resizing; store-distributed sandboxed builds now direct users to WAV instead of exposing unsupported external MP3 transcoding.

## Choose the right package

- **Linux x64 (APPIMAGE):** `session-craft-0.1.6-linux-x64.AppImage` — Portable Linux desktop package
- **Linux x64 (DEB):** `session-craft-0.1.6-linux-x64.deb` — Debian, Ubuntu, Mint, and compatible systems
- **Linux x64 (RPM):** `session-craft-0.1.6-linux-x64.rpm` — Fedora, RHEL, openSUSE, and compatible systems
- **Windows x64:** `session-craft-0.1.6-windows-x64-setup.exe` — Guided Windows installer

## Before you install

- Imported songs and practice-session state stay on the desktop unless you deliberately write an exported backing track.
- Keep the installer filename and checksum together when handing a package to another machine.
- Read the [help center](https://hannes-software.com/session-craft/help/) for supported inputs, workflow boundaries, and troubleshooting.
- Optional licensed features are described on the website without changing the free Community Edition download.

Full product details: https://hannes-software.com/session-craft/
