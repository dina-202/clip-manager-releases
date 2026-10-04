# Clip Manager releases

Public Windows x64 updates for Clip Manager. The development repository is maintained privately.

Existing installations of version 0.2.4 or later can use **Workspace & history → App updates → Check for updates** or the tray menu. Updates are verified with a pinned Ed25519 signature and SHA-256. An encrypted workspace backup is created before installation.

The app opens directly on this PC. Version 0.2.8 protects private Windows settings with the Windows account and automatically authorizes its local API. Connected accounts, campaigns, videos and history stay in the local workspace. Keep an exported backup recovery key private if you need to move the workspace to a different PC or Windows account.

Public update packages preserve existing video tools in the desktop profile. A fresh installation needs FFmpeg and ffprobe on PATH or the private bootstrap installer.

[Download the latest release](https://github.com/dina-202/clip-manager-releases/releases/latest)

Windows installer code signing is not enabled. Update metadata signatures authenticate the downloaded update; application code remains inspectable.
