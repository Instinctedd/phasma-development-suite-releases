# Phasma Development Suite

Windows installers and automatic-update files for Phasma Development Suite.

[Download the latest Windows x64 installer](https://github.com/Instinctedd/phasma-development-suite-releases/releases/latest)

Download `Phasma-Development-Suite-Setup-<version>-x64.exe` from the release assets and run it. No GitHub account, GitHub CLI, Node.js or npm is needed. This initial release is unsigned; Windows may show an unknown-publisher warning.

From v0.1.2, installation automatically creates `Documents\Phasma Development Suite\Vault` and the app opens it without asking you to select a folder. Existing installations keep their previously selected vault. Provider account sign-in is configured separately inside the app using the official local Codex or Claude Code runtime.

From v0.1.1, Phasma checks for updates when it opens and applies an available update before opening your workspace. Choose **Open app now** to skip waiting. If it is already open, updates download in the background and the blue **Update available** button lets you choose when to apply and restart. Your external vault and preferences are preserved.

Existing v0.1.0 users need one upgrade to v0.1.1 or later to gain automatic updates; use the latest installer above. Future releases update inside Phasma. Users with access to the original private repository may also use v0.1.0's Settings → Updates to obtain that first upgrade.

This repository contains release files and this README only. App source is maintained privately. The automatically generated Source code archives contain this release repository's README, not the application installer.
