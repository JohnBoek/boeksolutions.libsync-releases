# BoekSolutions LibSync

A Windows desktop tool for one-way, profile-based file synchronization with automatic backups and safe orphan-file handling.

## ⬇️ Download

Grab the latest installer from **[Releases](../../releases/latest)**. Run the `.exe` and follow the wizard. Installation and removal apply to all Windows users and require administrator approval; run LibSync normally without administrator rights.

Read the **[user guide](https://boeksolutions.nl/help/libsync.html#en-start)** in English or Dutch. The same guide is installed with the app: choose **Help → User guide** or press **F1**, even from dialogs. It works offline. You can also download `Help.html` from the latest release and open it in your browser.

## What it does

- **Profile-based sync.** Define a source folder, one or more target folders, and an optional staging/backup folder — save profiles for reuse.
- **Safe by default.** Deletions are never applied without confirmation; orphaned files get a dedicated resolution dialog (skip, delete, copy back to source, or rename).
- **Preview before you sync.** See exactly what will change before anything is written.
- **Restore.** Roll back to a previous backed-up run.
- **8 languages**, including Dutch, English, German, French, Spanish, Frisian — and Klingon and Elvish, for the curious.
- **Three themes**: Light, Dark, and "Book" (a warm parchment-and-gold look).
- **Automatic update checks**, so you're always notified when a new version is available.

## Requirements

- Windows 10/11, x64

## Updates

The app checks for new versions on startup and prompts you when one's available — no manual downloading required after your first install.

## Security

Every installer here is a tested Release build, manually verified before publishing. Note: installers are not yet code-signed, so Windows SmartScreen may warn on first run — click "More info" → "Run anyway" if so. If a Release asset in this repository ever looks tampered with or doesn't match what you'd expect from an official BoekSolutions release, **do not run it** — open an issue here instead.
