# Release Notes

## Jumper 2024.08.16 (311)

### 🔨 Improvements
- Added **Acknowledgements** menu item to the **Help** menu in `Jumper.app`.
- More minor improvements to the main `Jumper.app` to make it look more like macOS System Settings. Thanks to everyone who offered feedback and ideas!
- Changed the font of the Jumper Workflow Extension and Premiere Extension to the macOS default font. Thanks for suggesting Iain Anderson!

### 🐞 Bug Fixes
- Fixed a spelling mistake in the Jumper Workflow Extension and Premiere Extension. Thanks for reporting Iain Anderson!
- Added workaround for selecting clips that have the same file name at the Finder level in Final Cut Pro. Thanks for reporting Iain Anderson!

---

## Jumper 2024.08.15 (306)

### 🔨 Improvements
- Various improvements to the main `Jumper.app` to make it look more like macOS System Settings. Thanks to everyone who offered feedback and ideas!

### 🐞 Bug Fixes
- Fixed some performance issues with installing and updating the Adobe Premiere Plugin.
- Fixed a bug where the **Paste Timecode** command would not trigger if it was assigned to the **clear** button. Thanks for reporting Iain Anderson!

---

## Jumper 2024.08.14 (292)

### 🔨 Improvements
- Fixed media table updates (websocket data was too fast for JavaScript renders) and removed Jumper Accessibility Helper validation call from Jumper Helper. Now using Jumper Helper `2024-08-14 (390)`.

---

## Jumper 2024.08.12 (286)

### 🔨 Improvements
- Various improvements to the main `Jumper.app`. There's now a toggle for granting Full Disk Access.

---

## Jumper 2024.08.10 (280)

### 🔨 Improvements
- Various improvements to the main `Jumper.app`. We now automatically restart the Accessibility Helper once granted Screen Recording Permissions.

---

## Jumper 2024.08.10 (271)

### 🔨 Improvements
- Various improvements to the main `Jumper.app`, with additional user messaging and spinners when things are happening behind the scenes.
- Prevent Jumper Helper from going to sleep by adding `NSAppSleepDisabled` to `Info.plist`.
- Jumper Helper now saves log files in `~/Library/Logs/jumper.log`
- Better error handling when a file path is not found on the system

---

## Jumper 2024.08.09 (256)

### 🎉 Woohoo!
- This is the first beta release of Jumper! Thanks for testing!