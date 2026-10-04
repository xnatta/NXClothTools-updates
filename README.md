# NX Cloth Tools — Windows updates

This repository distributes installers and online updates for NX Cloth Tools. It does not contain clothing packs or project files.

## Install

Download the `NXClothTools-<version>-Setup-x64.exe` asset from the [latest release](https://github.com/xnatta/NXClothTools-updates/releases/latest).

Windows 10 version 1809 or later, or Windows 11, x64. The installer includes the runtime; a separate .NET installation is not needed.

If you already use a version older than 0.14.0, install 0.14.0 or later once over the existing installation. No uninstall is necessary.

## Update

Open **Check updates** in the app header. Download and review the update, then choose **Save & update**. The app saves a recovery copy of the open project, installs the new version, and reopens the saved project.

Automatic checks can be disabled in the update window. Nothing is installed until you choose to update.

Projects and exports are stored separately from the application. Recovery copies are saved under `Documents/NXClothTools/projects/recovery`.

The update source is `xnatta/NXClothTools-updates`. Releases include the installer and a matching `.sha256` file. The app verifies the download before installation.
