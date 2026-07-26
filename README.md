# ClinikEHR Desktop — downloads

Installers for the ClinikEHR desktop application. Get the latest from
**[Releases](../../releases)**.

This repository contains no application code — only published installers and their
update metadata.

## Which file do I download?

| Edition | Windows | macOS |
|---|---|---|
| **Pharmacy** | `ClinikEHR-Pharmacy-POS-<version>-x64.exe` | `…-arm64.dmg` (Apple silicon) · `…-x64.dmg` (Intel) |
| **Diagnostics / Lab** | `ClinikEHR-LIMS-Desktop-<version>-x64.exe` | `…-arm64.dmg` · `…-x64.dmg` |
| **ClinikEHR** | `ClinikEHR-Desktop-<version>-x64.exe` | `…-arm64.dmg` · `…-x64.dmg` |

On a Mac, choose **arm64** for M1/M2/M3/M4 and **x64** for Intel. Linux `.AppImage`
and `.deb` builds are also published.

Not sure which edition you use? Ask your clinic administrator.

## Installing

Run the installer and follow the prompts. Your existing account works as-is — sign in
with the same details you use in the browser.

### The security warning on first launch is expected

These builds are not yet code-signed, so your operating system will warn you once. The
warning is about the missing signature, not about the software.

**macOS** — "cannot be opened because Apple cannot check it for malicious software":
right-click (or Control-click) the app, choose **Open**, then **Open** again. Once only.

**Windows** — "Windows protected your PC": click **More info**, then **Run anyway**.

## Updates

**Windows** updates itself — it checks for a new release periodically, downloads in the
background, and applies it the next time you quit.

**macOS** does not update itself yet. Download the newer `.dmg` from Releases and
install it over the old one. Your data and sign-in are preserved.

## What the desktop app adds

It shows the same application you use in a browser, plus a few things a browser cannot
do: silent receipt printing to a thermal printer, a full-screen till mode, and local
storage that keeps working when the internet drops and syncs once it returns.

## Reporting a problem

Open **Help → About** and include both version numbers shown there, along with your
operating system and edition.
