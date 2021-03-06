---
slug: 2020-08-02-updates-july-2020
title: Updates (July 2020)
authors: eric
date: 2020-08-02
---

This will probably be our last monthly update post! Starting from August we will transition to weekly updates as needs arise.

# New lock screen clocks

New, OnePlus-inspired lock screen clocks have been added! [Go check out the full-quality video over at our Twitter.][twitter-video-link]

[twitter-video-link]: https://twitter.com/Bliss_ROMs/status/1284537875405565952

# Changes in BlissRoms

The following are new changes in BlissRoms 12.9 and 12.10:

## Bug fixes:

- When the brightness slider position was set to QQS, and when the dark mode tile was toggled, sometimes there would be two brightness sliders. This has been fixed.
- Fixed force close for some devices (Realme XT) on lock screen charging info.
- Fixed padding between battery and signal icon
- Fixed force close for Wi-Fi only devices
- Fixed external adaptive Settings dashboard icons not theming
- Fixed no brightness slider and Quick Settings panel when rotated to landscape mode
- Fixed various network traffic issues
- Fixed Edge Lighting sometimes showing up on home screen
- Fixed various screen stabilization problems
- Updates and fixes to notch-city display cutout mode
- Fixed OnePlus switch disabled thumb color
- Fixed accent preset summary and selected value in “Blissify > Themes”
- Fixed slim recent switch not showing the enabled state properly
- Fixed status bar header’s buggy layout when the single image option is selected, but there is no image selected yet
- Fixed showing unlock screen directly bug
- Fixed network traffic visibility on status bar
- Improve DT2W (double tap to wake) on AOD (always-on display)
- Improved FOD (fingerprint-on-display) views
- Fixes and updates to lockscreen shortcuts

## UI changes:

- Unified options in “Blissify > Statusbar”, everything can be found in one place now
- Reordered some stuff in “Blissify > QS” depending on their importance

## Added features:

- Add 5 new OnePlus-inspired lockscreen clocks (see above!)
- Thanks to @Roger_T for the designs!
    - OnePlus Numbers
    - Minimalism
    - OnePlus Roman dial
    - OnePlus analog
    - OnePlus minimal
- QS “DISCO” mode has been added, thanks to the POSP team!
- Random accent mode has been added, thanks to the msm extended team!
- Navbar pulse has been added, thanks to the DU team for porting it to Android 10!
- Added random accent to tile label
- Added support for per app network isolation
- Added option to enable full screen for all apps. This is different option from the “long apps” feature, which is for old, legacy apps.
- Improved aspects of volume panel (Notification row among other changes)
- Brought back brightness slider in expanded QS panel when QQS (top) and QQS (bottom) are selected.
- Added Ethereal primary theme.
- A lot of improvements to Notch city, thanks to POSP and crdroid team!
- Update QS data usage more frequently
- Improved QS data handling some more
- Increased size of all analog clocks
- Fixed accent and gradient mode for QS tiles
- Improved QS tint modes
- Added SBC HD Bluetooth codec
- Added Bluetooth dual channel mode
- Added option to select SBC HD by default
- Added A2DP codec priority option (preferred codec)
- More Bluetooth updates
- More SQLite improvements
- Enabled Zygote pre-forking (USAP pool). This will make apps launch faster!
- Added VoWi-Fi icons. This is disabled by default, so ask your maintainer to enable it only if your device supports the function.
- Added notification counters (shows number of notifications in status bar)
- Added back button for free-form windows
- Update heads up QS tile icon
- Add R style icon shapes
- Transparent QS background (not yet added, depending on device releases may vary)
- About Phone animations have been removed and changed to Lottie animations like other sections, as requested by many users. Thanks to our lead designer, Roger Truttmann, for adding these animations!
- Added transparent status bar QS background
- Removed search bar in launcher
- Added ability to disable glance widget in launcher
- Added stock navbar layouts (compact, right leaning, left leaning, etc.)
- Launcher additions below: (thanks to all contributors and the AICP team!)
    - Change row and column count
    - Clear all recents with swipe down
    - Toggle app labels
    - Hide top apps prediction row in app drawer
    - Icon size setting
    - Icon support

## Notes:

- Navbar pulse will be hidden if navbar is hidden, or IME space is hidden when navbar is set to gesture mode. This is not a bug.
- For transparent statusbar background, QS background opacity has to be reduced to see the effect!

We’ve also added more translations, thanks to contributors on our Crowdin. [Go translate BlissRoms for your device here!][blissroms-crowdin]

[blissroms-crowdin]: http://translate.blissroms.com/

# Dropped devices

We are discontinuing support for the following devices:

- Realme 5 Pro (RMX1971)
- Asus Zenfone Max Pro M1 (X00T)

We would like to thank the maintainers that maintained these devices up to this date. If you wish to maintain for any of the devices above, or apply to maintain for a new device, [submit a maintainer application here.][maintainer-application]

[maintainer-application]: https://blissroms.com/maintainers/

And that’s it for this month! Leave a comment down below on your thoughts!