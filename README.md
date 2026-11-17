# TypeBlink releases

Downloads for **TypeBlink** (called TypeAhead before 0.5.0), inline AI autocomplete for every text
field, running entirely on your own computer. For macOS, Windows and Ubuntu. By Dutt Mistry and
Rohan Bhoi.

| System | Download |
|---|---|
| macOS 14 or newer, Apple silicon | [TypeBlink.dmg](https://github.com/duttencodedots/TypeAhead-releases/releases/latest/download/TypeBlink.dmg) |
| Windows 10 / 11, 64-bit | [TypeBlink-Setup-x64.exe](https://github.com/duttencodedots/TypeAhead-releases/releases/latest/download/TypeBlink-Setup-x64.exe) |
| Ubuntu 22.04 / 24.04, 64-bit | [TypeBlink_amd64.deb](https://github.com/duttencodedots/TypeAhead-releases/releases/latest/download/TypeBlink_amd64.deb) |

[All releases](https://github.com/duttencodedots/TypeAhead-releases/releases)

## Install on macOS

1. Open `TypeBlink.dmg` and drag TypeBlink to Applications.
2. Open TypeBlink. If macOS says it cannot verify the app, click **Done**, then go to
   System Settings → Privacy & Security and click **Open Anyway**.
3. Allow TypeBlink in System Settings → Privacy & Security → Accessibility.

## Install on Windows

1. Run `TypeBlink-Setup-x64.exe`. If Windows shows "Windows protected your PC", click
   **More info**, then **Run anyway** (the installer is not signed). It installs for your user
   only; no administrator password is needed.
2. The setup assistant downloads the model. The app lives in the system tray.

## Install on Ubuntu

1. `sudo apt install ./TypeBlink_amd64.deb`
2. Open the app from the app grid. The setup assistant adds it as a keyboard input source;
   select it in the top bar's keyboard menu (or press Super + Space).

On Windows and Ubuntu the installed app still shows its earlier name, TypeAhead, for now.

The app finds new versions here by itself: **Check for Updates…** in its menu installs them in
one click (macOS from 0.3.3, Windows and Ubuntu from 0.4.0).

This repository holds only release downloads.
