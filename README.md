# SPC Accounting

Keyboard-first double-entry accounting for Mac and Windows. Your books live on a pendrive.

This repository holds the installers only.

## Download

| | |
|---|---|
| **Windows** | [SPC-Accounting-Windows-Setup.exe](https://github.com/nnppss/spc-release/releases/latest/download/SPC-Accounting-Windows-Setup.exe) |
| **Mac — Apple silicon** (M1 and later) | [SPC-Accounting-Mac-arm64.dmg](https://github.com/nnppss/spc-release/releases/latest/download/SPC-Accounting-Mac-arm64.dmg) |
| **Mac — Intel** | [SPC-Accounting-Mac-x64.dmg](https://github.com/nnppss/spc-release/releases/latest/download/SPC-Accounting-Mac-x64.dmg) |

Not sure which Mac you have? Apple menu → About This Mac: "Chip: Apple M…" is Apple silicon, "Processor: Intel" is Intel.

All versions: [Releases](https://github.com/nnppss/spc-release/releases).

## Install

- **Mac:** open the `.dmg` and drag the app to Applications. The first time you open it, macOS refuses because the app isn't signed: open System Settings → Privacy & Security and click **Open Anyway**. Do this again after each update.
- **Windows:** download the `.exe` and run it. SmartScreen asks once: click **More info → Run anyway**.

## The pendrive

Format the pendrive as **exFAT**. It's the only format both Mac and Windows can read and write, so the same books open on either one.

- **Working pendrive:** connect it and choose its workspace before signing in. For a new drive, click **Add workspace**, pick the books start date and set a password. Quit the app before you eject it.
- **Backup pendrive:** in **Settings → Books**, click **Back up to pendrive**, pick a second drive, check the destination and click **Confirm backup**. The copy holds the books, the password and the restore history, and you can work from it directly by choosing it on the workspace screen. If the drive already has `SPC-Data`, the new copy gets a dated folder.

## Updates

The app checks for a new version when it opens, and from **Help → Check for Updates**.

- **Windows** downloads the update and asks you to restart.
- **Mac** opens the download page. Replace the app in Applications with the new one.
