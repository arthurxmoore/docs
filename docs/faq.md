# Frequently Asked Questions

Got ideas or questions? Post them on our [Discussions page](https://github.com/GetJumper/docs/discussions) or [Discord](https://discord.com/invite/3JFNYAfwSb).

You can also email us here: [hello@getjumper.io](mailto:hello@getjumper.io)

---

### How fast is the search?

We’ve tested on a few different machines (MBP M1, Windows i5 laptop, 2019 Ryzen desktop) and all were able to search through roughly 100 hours of footage in about 0.2 seconds.

---

### How long does the processing take?

A MacBook M1 Pro can process around 15 minutes of footage in 1 minute.

---

### Is any part of my footage uploaded during processing?

No, we don’t upload the data processed from your footage, or any part of your footage. The processing is done locally and stays on your computer.

---

### Does Jumper require an Internet connection?

Jumper only goes online for license verification. Once your license key is verified, you can run everything offline.

---

### Does processing the footage create any significant amount of data on one's computer?

When processing footage, Jumper generates some cache files. The size of the cache files varies depending on a few factors like resolution etc. Our initial analysis shows about 1-1.5 mb of cache per 10s of footage.

---

### Accessibility Permission

Jumper requires Accessibility Permission to trigger commands and menu bar items in Final Cut Pro through macOS's built-in Accessibility Automation.

We use the Accessibility API to programatically "click" on buttons and menu bar items - similar to how Automator, Keyboard Maestro, BetterTouchTool, etc. works.

---

### Screen Recording Permission

Jumper requires the Screen Recording permission to detect things on your screen when using Final Cut Pro.

This is a new Security Setting that started in macOS Catalina.

Jumper does not record the screen.

We're not "recording" the screen as a video like a QuickTime Player or a screen recording application would do - we're simply using Apple's APIs to get access to information about the contents of the screen.

We use Apple's API's to get the name of windows that are open.

We also use the API's to help detect when Final Cut Pro is playing and paused, by "looking" at the play/pause button in the Viewer.

Nothing is saved to disk. Nothing is transmitted online.

We simply use Apple's APIs to access screen information.

We also have the option of OPTIONALLY sending screenshots when you submit feedback.

Lots of other applications like [Bartender](https://www.macbartender.com/Screen-Recording-Permission/) and [BetterTouchTool](https://folivora.ai/blog/post/13011/) have this same limitation.

We use the same techniques as the totally open-source [CommandPost](https://commandpost.io), so you can always inspect their code to see what's going on.

---

### Full Disk Access Permission

Jumper requires Full Disk Access to read Final Cut Pro's Preferences File (`~/Library/Preferences/com.apple.FinalCut.plist`) and the current Final Cut Pro Command Set.

Due to macOS's very tight security in recent releases, we need explicit permission to read files inside the user's `Library` folder.

We only use this permission to read Final Cut Pro preferences files.

---

### What hardware was used in the video?

In the video Jumper was running a MacBook Air M2.

---

### Can I transfer the Analysis Files to another editor’s machine?

Yes, to transfer the Analysis Files on macOS:

- Open the `Terminal.app` from Spotlight, and navigate to the cache directory:

```
open ~/Library/Application\ Support/
```

Then you can copy the `jumper-cache` folder to the same location on the other editor’s machine.

---

### Will copying the cache overwrite existing files on the receiving machine?

No, copying the Analysis Files will be additive.

It will not overwrite existing files but add to them.

---

### Can I change the location of my Analysis Files folder?

Yes, you can change the location of your Analysis Files Folder under the `Settings` tab in Jumper.

---

### How does Jumper handle multi-channel audio?

Currently Jumper only processes audio from the first channel that has valid dialogue.

In a future update, Jumper will process all audio channels.