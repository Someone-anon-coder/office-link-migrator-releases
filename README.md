# Office Link Migrator: downloads

Installers for **Office Link Migrator**, a Windows app that finds every link inside folders of
Excel, Word and PowerPoint files, flags the broken ones, and rewrites old file-server paths to
new ones in safe copies.

**Download:** [latest release](https://github.com/Someone-anon-coder/office-link-migrator-releases/releases/latest)
· **Website and help:** <https://office-link-migrator.aayush-c2684.workers.dev>

This repository holds release files only; it contains no source code.

## Install

1. Download `OfficeLinkMigrator-Setup-<version>.exe` from the latest release.
2. Optional: check it against `SHA256SUMS.txt` in the same release. In PowerShell:
   ```
   Get-FileHash .\OfficeLinkMigrator-Setup-0.1.0.exe
   ```
3. Run it. It installs for your user only and needs no administrator rights.

The installer is not code-signed yet, so Windows SmartScreen may show "Windows protected your
PC". Choose **More info**, then **Run anyway**.

Windows 10 (1809 or later) and Windows 11, 64-bit. No Office or Python needed.

## Free and paid

Scanning, reports and previews are free. Applying changes needs a licence. See the
[website](https://office-link-migrator.aayush-c2684.workers.dev/#pricing).

Your documents never leave your PC; the only network call is licence activation. See the
[privacy policy](https://office-link-migrator.aayush-c2684.workers.dev/privacy).

## Support

office-link-migrator@proton.me
