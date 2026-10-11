# Changelog

## 0.3.4

- Smoother switches on several monitors: each monitor draws in step with its own refresh rate.
- Update checks always see the newest version, even right after a release.
- The log records frames and the slowest frame gap per monitor for every switch.

## 0.3.3

- A small release to try out updating from 0.3.2. No other changes.

## 0.3.2

- Each release now holds just `Hyperlane-win-Setup.exe`; the updater's files moved to a separate Update feed release.
- 0.3.0 and 0.3.1 can't see updates from here on: install 0.3.2 once with the Setup.exe.

## 0.3.1

- A small release to try out updating from 0.3.0. No other changes.

## 0.3.0

- Installs like a real app: a per-user installer with a Start menu entry, an Installed apps entry with Uninstall, and start at sign-in.
- Updates itself: checks once a day, shows what's new in Settings › About and the tray menu, and downloads only what changed. Beta versions are opt-in.
- `Hyperlane.exe update` and `update install` from a terminal.
- An app icon.

## 0.2.0

The first public build.

- Twelve transitions with adjustable speed, easing, axis and direction.
- Ctrl+Win+← / → replace Windows' own slide; Ctrl+Alt+1…9 and Ctrl+Alt+0 jump between desktops; mouse buttons 4 and 5 can switch too.
- Animation starts from the last picture of the destination desktop.
- All monitors animate together.
- Windows 11-style Settings with a live preview, a tray icon with the desktop number, and a command line.
