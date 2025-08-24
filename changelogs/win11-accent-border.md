## 1.0.2 ([Aug 24, 2025](https://github.com/ramensoftware/windhawk-mods/blob/f251191b1143234f2924240a3cca66f31a0e4947/mods/win11-accent-border.wh.cpp))

Fixes #2348

Something appears to be messing with DWM registry keys in WinAppSDK MSIX packaged apps that make them not update in sync. This also affects DWM APIs and messages. Explorer's keys appear to behave correctly and update in sync with everything else and contain the same value so use those instead.

## 1.0.1 ([Jul 29, 2025](https://github.com/ramensoftware/windhawk-mods/blob/8b3ae1b62a9a0eb64e21503f00ee2592631de301/mods/win11-accent-border.wh.cpp))

React to accent color changes and target border-only windows.

## 1.0.0 ([Jun 6, 2025](https://github.com/ramensoftware/windhawk-mods/blob/1927abe816b6ff1d930fce7dc46ac527167bfd25/mods/win11-accent-border.wh.cpp))

Initial release.
