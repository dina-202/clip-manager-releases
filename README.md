# Clip Manager releases

Public Windows x64 update downloads for Clip Manager. The development repository is maintained separately.

## Update the app

Existing installations of version 0.2.4 or later can use **Workspace & history → App updates → Check for updates** or the tray menu. Download the update, then choose **Back up and install update**. Updates are verified with a pinned Ed25519 signature and SHA-256, and the app creates an encrypted workspace backup before installation.

Installations before 0.2.4 need the private bootstrap installer once to enable in-app updates and preserve their bundled video tools. Alternatively, install FFmpeg and ffprobe on PATH before using a public update package. Public packages preserve video tools already saved in the desktop profile. A fresh installation requires FFmpeg and ffprobe on PATH or the private bootstrap installer.

[Download the latest release](https://github.com/dina-202/clip-manager-releases/releases/latest)

Your campaigns, Instagram connections, videos and history stay in your local workspace. Windows code signing is not enabled for this release.
