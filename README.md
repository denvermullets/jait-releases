# JAIT Desktop releases

Download page for [JAIT Desktop](https://justanotherissuetracker.com), the native macOS client for JAIT (Just Another Issue Tracker).

This repo only holds published Releases. There's no source code here.

## Download

**[Download JAIT for macOS (Apple silicon)](https://github.com/denvermullets/jait-releases/releases/latest/download/JAIT.dmg)**

This link always points to the newest Release.

## Requirements

- A Mac with Apple silicon (M1 or later). Intel Macs aren't supported.
- A JAIT account.

## Install

1. Download `JAIT.dmg` from the link above.
2. Open it and drag **JAIT** onto the **Applications** folder.
3. Eject the disk image, then open JAIT from Applications.
4. Sign in with your JAIT account.

The app is signed and notarized by Apple, so it opens without any Gatekeeper warnings.

Run JAIT from `/Applications`. If you open it straight from the disk image or from Downloads, macOS may run it from a read-only location and the app won't be able to update itself.

## Updates

JAIT checks for Updates on its own. It checks at launch, about every 6 hours while it's running, and when the Mac wakes from sleep. When an Update is found it downloads in the background, and a **↑ version ready** chip shows in the status bar. The Update installs the next time you quit JAIT. You can also choose **Restart now**.

You'll find the installed version, a **Check for updates** button and the automatic-check toggle in **Settings → Updates**.

If JAIT can't install an Update itself, it offers you the DMG instead. Download it and install it the same way as above, replacing the old copy.

## Release notes

Each [Release](https://github.com/denvermullets/jait-releases/releases) lists what changed in that version. JAIT also shows the notes for every version you've missed when an Update is ready.

## Older versions

Every past Release, with its DMG, is on the [releases page](https://github.com/denvermullets/jait-releases/releases).
