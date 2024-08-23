# Release Notes

### Jumper 2024.08.23 (394)

**🔨 Improvements**

- Minor user interface improvements to the Final Cut Pro Workflow Extension and Premiere Extension. Thanks for all your feedback!
- Added a **Open Cache** button in the Media panel.
- `Jumper.app` is now responsible for installing the Adobe Premiere plugin. `JumperHelper.app` will be updated in the next beta, as currently it can stall on first load—requiring you to manually restart in `Jumper.app`.

---

### Jumper 2024.08.22 (383)

**🔨 Improvements**

- Minor user interface improvements to the Final Cut Pro Workflow Extension and Premiere Extension. Thanks for all your feedback!
- The main `Jumper.app` now checks for updates automatically on startup. Automatic updates are now on by default.
- Increased the minimum size of the Final Cut Pro Workflow Extension.

---

### Jumper 2024.08.22 (375)

**🔨 Improvements**

- Minor user interface improvements to the Final Cut Pro Workflow Extension and Premiere Extension. Thanks for all your feedback!
- Added **Recent Searches** feature to the Final Cut Pro Workflow Extension and Premiere Extension.
- Improved the main `Jumper.app` so it doesn’t show Final Cut Pro information if Final Cut Pro isn’t installed.
- `Jumper.app` now runs on macOS Monterey. Thanks for suggesting wandering.ant!

---

### Jumper 2024.08.21 (366)

**🔨 Improvements**

- Minor user interface improvements to the Final Cut Pro Workflow Extension and Premiere Extension. Thanks for all your feedback!
- Updated the Final Cut Pro Workflow Extension icon.

---

### Jumper 2024.08.18 (336)

**🔨 Improvements**

- The help buttons in the main `Jumper.app` now go to a placeholder documentation site.
- Minor user interface improvements to the Jumper Workflow Extension. Thanks for suggesting Iain Anderson!
- We now use delta updates for faster incremental updates. For example, if we just make a minor tweak to the user interface, you don't need to download the 1.44GB application again - you only download the files that changed.
- Increased the minimum size of the Final Cut Pro Workflow Extension.

---

### Jumper 2024.08.16 (311)

**🔨 Improvements**

- Added **Acknowledgements** menu item to the **Help** menu in `Jumper.app`.
- More minor improvements to the main `Jumper.app` to make it look more like macOS System Settings. Thanks to everyone who offered feedback and ideas!
- Changed the font of the Jumper Workflow Extension and Premiere Extension to the macOS default font. Thanks for suggesting Iain Anderson!

**🐞 Bug Fixes**

- Fixed a spelling mistake in the Jumper Workflow Extension and Premiere Extension. Thanks for reporting Iain Anderson!
- Added workaround for selecting clips that have the same file name at the Finder level in Final Cut Pro. Thanks for reporting Iain Anderson!

---

### Jumper 2024.08.15 (306)

**🔨 Improvements**

- Various improvements to the main `Jumper.app` to make it look more like macOS System Settings. Thanks to everyone who offered feedback and ideas!

**🐞 Bug Fixes**

- Fixed some performance issues with installing and updating the Adobe Premiere Plugin.
- Fixed a bug where the **Paste Timecode** command would not trigger if it was assigned to the **clear** button. Thanks for reporting Iain Anderson!

---

### Jumper 2024.08.14 (292)

**🔨 Improvements**

- Fixed media table updates (websocket data was too fast for JavaScript renders) and removed Jumper Accessibility Helper validation call from Jumper Helper. Now using Jumper Helper `2024-08-14 (390)`.

---

### Jumper 2024.08.12 (286)

**🔨 Improvements**

- Various improvements to the main `Jumper.app`. There's now a toggle for granting Full Disk Access.

---

### Jumper 2024.08.10 (280)

**🔨 Improvements**

- Various improvements to the main `Jumper.app`. We now automatically restart the Accessibility Helper once granted Screen Recording Permissions.

---

### Jumper 2024.08.10 (271)

**🔨 Improvements**

- Various improvements to the main `Jumper.app`, with additional user messaging and spinners when things are happening behind the scenes.
- Prevent Jumper Helper from going to sleep by adding `NSAppSleepDisabled` to `Info.plist`.
- Jumper Helper now saves log files in `~/Library/Logs/jumper.log`
- Better error handling when a file path is not found on the system

---

### Jumper 2024.08.09 (256)

**🎉 Woohoo!**

- This is the first beta release of Jumper! Thanks for testing!