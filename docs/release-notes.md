# Release Notes

### Jumper 2024.09.09 (682)

**🔨 Improvements**
- Improved the user interface for recent searches in the Final Cut Pro Workflow Extension and Adobe Premiere Extension. Thanks to all our beta testers for their feedback on this!
- Improved the Uninstall Utility for scenarios where you might have a different Analysis files folder for Final Cut Pro and Adobe Premiere.
- We now ensure that the Jumper Engine and Final Cut Pro Automation Engine we're launching are from the same application bundle as the main Jumper application. This improves reliability for beta testers who might have multiple versions of Jumper on their system.

---

### Jumper 2024.09.07 (672)

**🔨 Improvements**
- We now restart the Jumper Engine and Final Cut Pro Automation Engine when doing an automatic update.
- Increased the brightness of the filename in the Thumbnails in the Final Cut Pro Workflow Extension and Premiere Extension.
- Restored the ability the right-click to open contextual menus on text fields through the Final Cut Pro Workflow Extension and Premiere Extension.
- Set a maximum height for the "Recent Searches" popover.
- Replaced the trashcan icon with an "X" icon for ignoring a clip in the Final Cut Pro Workflow Extension and Premiere Extension.
- Improved the sorting order in the Media Panel in the Final Cut Pro Workflow Extension and Premiere Extension.


**🐞 Bug Fixes**
Fixed a bug when selecting checkboxes in the Media Panel. Thanks for reporting Marc Bach!
Fixed a bug where the "Process Selection" button could be disabled for a few seconds.

---

### Jumper 2024.09.06 (655)

**🔨 Improvements**
- We now take into account the Library name when selecting an Event. Thanks for suggesting Iain Anderson!


**🐞 Bug Fix**
- The Final Cut Pro Automation Engine Debug Console no longer opens at launch. Sorry about that folks!
- Fixed a user interface glitch where "Process Selection" was written twice in the Media panel button.

---

### Jumper 2024.09.05 (645)

**🔨 Improvements**
- The license key is automatically submitted after you paste in a license key.
- Improved recent search feature in the Final Cut Pro Workflow Extension and Premiere Extension.
- Improved tooltips in the Final Cut Pro Workflow Extension and Premiere Extension.
- Improved the visual thumbnails interaction in the Final Cut Pro Workflow Extension and Premiere Extension.
- General improvements to the Media panel user interface in the Final Cut Pro Workflow Extension and Premiere Extension.
- Improved error messages and alerts in the Final Cut Pro Workflow Extension and Premiere Extension.

---

### Jumper 2024.09.04 (636)

**🔨 Improvements**
- We now always make sure the Search field has focus when changing panels - i.e. when going from Visuals to Speech, or Media to Search.

---

### Jumper 2024.09.02 (614)

**🔨 Improvements**
- If you're in List mode in Final Cut Pro and you search in Jumper, we now go back to List mode once the search has completed. Thanks for suggesting Matthieu Laclau!
- Various improvements to the Media Panel in the Final Cut Pro Workflow Extension and Premiere Extension. It now works in pages for better performance with massive Final Cut Pro libraries and Premiere projects.
- Improved the communication between the Final Cut Pro Workflow Extension and the Final Cut Pro Automation Engine.
- Improved the main Jumper.app to make it more obvious that you don't require special macOS Permission to use Jumper with Adobe Premiere.
- We now write the Final Cut Pro Automation Engine log files to the same folder as the other log files.

**🐞 Bug Fix**
- Fixed a bug where the Final Cut Pro Automation Engine would fail to find the Final Cut Pro Viewer on the macOS 15 Sequoia beta. Thanks for reporting Mitchell Harris!

---

### Jumper 2024.08.31 (572)

**🔨 Improvements**
- Major under-the-hood improvements with how the Jumper Engine communicates with the Final Cut Pro Automation Engine. This should hopefully fix some issues some users were having with macOS Sequoia and the Final Cut Pro Workflow Extension. If you're still having issues, please reach out via email, GitHub or Discord.
- Various user interface improvements in the Final Cut Pro Workflow Extension and Adobe Premiere Extension related to scrolling and overflow.
- We now disable the License Key field whilst the license is being validated.

---

### Jumper 2024.08.30 (557)

**🔨 Improvements**
- Various improvements to the user interface in the Final Cut Pro Workflow Extension and the Adobe Premiere Extension.
- Fixed the EULA formatting in the download DMG. It now displays correctly in Dark Mode.
- Improved how we handle automatic updates in the main Jumper application.

---

### Jumper 2024.08.29 (534)

**🔨 Improvements**
- Various user interface improvements for the Adobe Premiere Extension and Final Cut Pro Workflow Extension.
- Improved the look of the Audio Search panel.
- Added "Connect" button to Video Search tab. Thanks for suggesting Kevin Luk!
- Improved the insertion controls in the Audio Search tab.
- Improved the Progress Bar when processing video and audio.
- Added the Uninstall tool to inside the download DMG.
- The Uninstall tool now optionally allows you to delete the processed audio and video files.
- The download DMG now has a EULA.
- Various text/label changes throughout Jumper to make it more consistent.
- We now show a spinner after entering a license key, whilst it awaits server validation.

---

### Jumper 2024.08.27 (500)

**🔨 Improvements**
- Various user interface improvements and minor text/wording changes.
- Fixed a regression in the previous release where we accidentally broke "Match Source", "Match Program" and other functions in the Adobe Premiere Extension. Apologies!
- The "buy" link now opens in a new Browser window.
- The "buy" link is now visible when Jumper is not licensed, and hides when licensed.
- Pressing the "Cancel" button when choosing an Analysis Folder in Adobe Premiere now behaves correctly.
- We now only show the recent popover if there are recent search values.
- Improved the visual look of the Splash Screen.
- Added feedback when the Jumper Engine is ready, but the Analysis files are not yet loaded for search and processing.

---

### Jumper 2024.08.26 (459)

**🔨 Improvements**
- Fixed various string truncation in the user interface.
- Added an auto-load thumbnail switch. Thanks for suggesting Iain Anderson!
- We now show a splash screen when Jumper Engine is still booting up.
- We now automatically restart the Jumper Engine if it's force quit whilst Adobe Premiere is running.
- Improved the "Total Files" counter in the Media panel.
- Added better controls in the Search panel for changing the "Add/Drop to timeline behaviour".

---

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