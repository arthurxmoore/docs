# Frequently Asked Questions

Got ideas or questions? Post them on our [Discussions page](https://github.com/GetJumper/docs/discussions) or [Discord](https://discord.com/invite/3JFNYAfwSb).

---

## How do I get access to the beta?

Go to the [Jumper Beta sign up form](https://forms.gle/Rk6ZezAaVzKPanH46) and make a request and we’ll get back to you as soon as we can.

---

##  I’ve signed up but still haven’t gotten a download link or license key?

We’re sending out beta access at a sustainable pace. We want to be able to assist and support without being overwhelmed. Please have patience and you should get your access soon.

---

## Accessibility Permission

Jumper requires Accessibility Permission to trigger commands and menu bar items in Final Cut Pro through macOS's built-in Accessibility Automation.

---

## Screen Recording Permission

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

## Full Disk Access Permission

Jumper requires Full Disk Access to read Final Cut Pro's Preferences File (`~/Library/Preferences/com.apple.FinalCut.plist`).

---

## How fast is the search?

We’ve tested on a few different machines (MBP M1, Windows i5 laptop, 2019 Ryzen desktop) and all were able to search through roughly 100 hours of footage in about 0.2 seconds.

---

## How long does the processing take?

A MacBook M1 Pro can process around 15 minutes of footage in 1 minute.

---

## What hardware was used in the video?

In the video Jumper was running a MacBook Air M2.