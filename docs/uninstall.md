# Uninstall

## macOS

You can download an Uninstall tool [here](https://download.getjumper.io/uninstall.zip).

Some folders will be protected by macOS, so you can either give the the Uninstall Tool **Full Disk Access** or remove certain files manually.

When you run the Uninstall tool you'll be presented with this:

![](/static/uninstall-01.png)

Click **Uninstall Jumper**.

You will be requested to enter your macOS password:

![](/static/uninstall-02.png)

Once completed you'll be presented with this:

![](/static/uninstall-03.png)

A file called `Jumper Uninstall Log.txt` will be added to your Desktop, and look something like this:

```
Deleted Files and Folders:
/Applications/Jumper.app
/Library/Application Support/Adobe/CEP/extensions/Jumper
/Users/chrishocking/.jumper/
/Users/chrishocking/Library/Logs/Jumper/
/Users/chrishocking/Library/Application Support/Jumper/
/Users/chrishocking/Library/Application Support/jumper-cache/
/Users/chrishocking/Library/Preferences/com.jumper.plist
/Users/chrishocking/Library/Application Support/Adobe/CEP/extensions/Jumper
/Users/chrishocking/Library/Caches/com.jumper
/Users/chrishocking/Library/Caches/com.jumper.jumperAccessibilityHelper
/Users/chrishocking/Library/Caches/SentryCrash/Jumper
/Users/chrishocking/Library/Caches/SentryCrash/Jumper Accessibility Helper
/Users/chrishocking/Library/HTTPStorages/com.jumper
/Users/chrishocking/Library/WebKit/com.jumper
/Users/chrishocking/Library/Application Scripts/com.jumper
/Users/chrishocking/Library/Application Scripts/com.jumper.WorkflowExtension
/Users/chrishocking/Library/Preferences/com.jumper.jumperAccessibilityHelper.plist

Undeleted Files and Folders (Manual Deletion Required):
/Users/chrishocking/Library/Containers/com.jumper.WorkflowExtension/
/Users/chrishocking/Library/Containers/com.jumper/
```

Alternatively if you want to uninstall manually...

Just drag the `Jumper.app` from your Applications folder to the Bin/Trash.

Jumper stores additional files in the following places:

- `/Library/Application Support/Adobe/CEP/extensions/Jumper`
- `~/.jumper/`
- `~/Library/Logs/Jumper/`
- `~/Library/Application Support/Jumper/`
- `~/Library/Application Support/jumper-cache/`
- `~/Library/Preferences/com.jumper.plist`
- `~/Library/Application Support/Adobe/CEP/extensions/Jumper`
- `~/Library/Caches/com.jumper`
- `~/Library/Caches/com.jumper.jumperAccessibilityHelper`
- `~/Library/Caches/SentryCrash/Jumper`
- `~/Library/Caches/SentryCrash/Jumper Accessibility Helper`
- `~/Library/HTTPStorages/com.jumper`
- `~/Library/WebKit/com.jumper`
- `~/Library/Application Scripts/com.jumper`
- `~/Library/Application Scripts/com.jumper.WorkflowExtension`
- `~/Library/Preferences/com.jumper.jumperAccessibilityHelper.plist`
- `~/Containers/com.jumper.WorkflowExtension/`
- `~/Containers/com.jumper/`

You can also manually remove these folders or use something like [AppCleaner](https://freemacsoft.net/appcleaner/).

---

## Windows

Delete the Jumper folder located in `C:\Users\YOUR-USER-NAME\AppData\Roaming\Jumper\`