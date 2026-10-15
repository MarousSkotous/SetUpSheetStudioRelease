# Setup Sheet Studio releases

Public update channel and installers for the Autodesk Fusion add-in
[Setup Sheet Studio](https://github.com/MarousSkotous/SetUpSheetStudio).

## Installation

- **Windows:** download `SetupSheetStudio-<version>-Windows.exe`, close
  Autodesk Fusion, and run the installer.
- **macOS:** download `SetupSheetStudio-<version>-macOS.pkg`, close Autodesk
  Fusion, and open the package in Installer.

Both installers place the add-in in the current user's Autodesk
`ApplicationPlugins` directory. User profiles and settings are kept separately
and are not removed by an update.

The installers are not currently code-signed. Windows SmartScreen or
macOS Gatekeeper may therefore ask for an additional confirmation. Published
SHA-256 values are available in the matching checksum file.

## Update channel

`update.json` is the stable machine-readable update manifest. Setup Sheet
Studio selects the entry for the current operating system, downloads it only
over HTTPS, and verifies its SHA-256 before opening the installer.
