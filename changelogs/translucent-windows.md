## 1.6.2 ([Aug 7, 2025](https://github.com/ramensoftware/windhawk-mods/blob/79eae3a6c6eedc3c5c77b7eedaaf2121ddfa71e9/mods/translucent-windows.wh.cpp))

* Fixed ExplorerPatcher taskbar theme bugs

## 1.6.1 ([Aug 5, 2025](https://github.com/ramensoftware/windhawk-mods/blob/a735c640a09ff65801f32dbe9e3b5f872380df19/mods/translucent-windows.wh.cpp))

* Custom painted theme parts made DPI aware
* Use system's accent palette for accent colorizer

## 1.6.0 ([Aug 4, 2025](https://github.com/ramensoftware/windhawk-mods/blob/87d392a2bf39e964f6ffdce92a6c68d5776f01a3/mods/translucent-windows.wh.cpp))

* Introduce custom painted windows theme parts using the Direct2D API
* Fix window flickering

## 1.5.1 ([Jun 30, 2025](https://github.com/ramensoftware/windhawk-mods/blob/e8d7c07e86637230df1c386a05f184da5b96f2d7/mods/translucent-windows.wh.cpp))

* Libraries are now loaded with the LOAD_LIBRARY_SEARCH_SYSTEM32 flag to prevent malicious or accidental dll hijacking. https://github.com/ramensoftware/windhawk-mods/issues/2063
* Fixed issue with the accent color not being the correct color in some programs, e.g. snippingtool.exe.
* Fixed a bug with system colors not being applied and unloaded correctly.
* Added logs.

## 1.5.0 ([Jun 4, 2025](https://github.com/ramensoftware/windhawk-mods/blob/0c981a8ec576c27ec33fcc70480c25083aecbb50/mods/translucent-windows.wh.cpp))

* Added Rainbow effect
* Additional windows theme parts are modified
* Added text alpha blending
* Changed BlurBehind to AccentBlurBehind
* Added DWMAPI immersive darkmode setting option
* Added window corner type setting option
* Fixed conflicting bugs with steamwebhelper.exe and firefox.exe programs
* Fixed conflicting bug with Slick Window Arrangement mod

## 1.4.2 ([Apr 14, 2025](https://github.com/ramensoftware/windhawk-mods/blob/afa6754ba136a6adbf459f0386bc7f13c68a707c/mods/translucent-windows.wh.cpp))

* Apply a workaround solution for background effects in windows Game Bar transparent overlay 
* Limit mod unloading to appropriate windows, fixes a bug during BlurBehind effect unloading

## 1.4.1 ([Apr 10, 2025](https://github.com/ramensoftware/windhawk-mods/blob/6d80a4ec94be318d3dfafdf9ef0b0f0b80185222/mods/translucent-windows.wh.cpp))

* Fix bug where previously both window states colors were needed to apply color effects
* Added a workaround solution for unloading the BlurBehind effect
* Added default color option support

## 1.4 ([Apr 10, 2025](https://github.com/ramensoftware/windhawk-mods/blob/3af9d8212ade28ef23003557cbd9ad77db77acf2/mods/translucent-windows.wh.cpp))

* Added color options for active and inactive window states
* Merge taskbar thumbnails border coloring with classic context menus setting

## 1.3 ([Apr 7, 2025](https://github.com/ramensoftware/windhawk-mods/blob/901ab88551bbba9ff79f8e1b8e7e5aeb29edb982/mods/translucent-windows.wh.cpp))

* Add rules for processes
* Fix Control Panel title bar text color not being applied when using Acrylic Blur Behind
* Fix Snipping Tool not being affected by mod

## 1.2 ([Apr 2, 2025](https://github.com/ramensoftware/windhawk-mods/blob/193118c7ae5451a3536bf39e1f029b4c701e7c76/mods/translucent-windows.wh.cpp))

* Added support for windows caption text color modification
* Added toggle button for classic context menu border colorization
* Added transparent border color support
* Added accent color support

## 1.1 ([Apr 1, 2025](https://github.com/ramensoftware/windhawk-mods/blob/f37b34243dbc6240ffb8bc7fe459f1b87556878a/mods/translucent-windows.wh.cpp))

* Added windows border color setting
* Added windows titlebar color setting
* Added recommendation for users to use black/dark themes like Rectify11

## 1.0 ([Mar 30, 2025](https://github.com/ramensoftware/windhawk-mods/blob/9dde9190d290ba16ca4de17293a09cb3cb3d8c23/mods/translucent-windows.wh.cpp))

Initial release.
