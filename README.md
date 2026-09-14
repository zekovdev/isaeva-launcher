# ISAEVA Launcher

Official Windows x64 downloads for ISAEVA Launcher by zekov.

**[Download the latest release](https://github.com/zekovdev/isaeva-launcher/releases/latest/download/ISAEVA-Launcher.exe)** · [Release notes](https://github.com/zekovdev/isaeva-launcher/releases) · [Discord](https://discord.gg/isaeva)

## Installation and updates

Download and run `ISAEVA-Launcher.exe`. Versions before 4.6.0 need this one-time
manual installation to connect to the official update feed.

On subsequent starts, the launcher checks for newer signed releases. Enable
**Install launcher updates automatically** in **Mods & Updates** to install them
automatically. Leave it disabled to receive a prompt before installation.
Network or verification failures keep the existing launcher available.

The launcher verifies release metadata with its embedded ISAEVA RSA-PSS public
key and verifies executable contents with SHA-256. This is package verification,
not Windows Authenticode signing; Windows may still show a reputation warning.

## Release assets

- `ISAEVA-Launcher.exe`: Windows x64 launcher.
- `ISAEVA-Launcher.exe.manifest.json` and `.sig`: signed metadata and proof.
- `update.json`: official update feed; payload links are pinned to one release.
- `LICENSE.txt`: project license. Dependency notices are also available in the app.

This repository distributes release packages. ISAEVA-specific development is by
zekov; retained Fishstrap/Bloxstrap code and third-party assets keep their license
notices. ISAEVA is an independent launcher and is not affiliated with Roblox.
