# yt-dlp-windows-context-menu
Adds buttons to the right click menu in Windows Explorer to download videos using yt-dlp. Works with YouTube and all the [services supported by yt-dlp](https://github.com/yt-dlp/yt-dlp/blob/master/supportedsites.md).

Simply copy a link and click the download button.

![](screenshot.png)

[**Download here**](https://github.com/sergidiazlopez/yt-dlp-windows-context-menu/archive/refs/heads/master.zip)

## Quick instructions
1. [Download and extract](https://github.com/sergidiazlopez/yt-dlp-windows-context-menu/archive/refs/heads/master.zip)
2. Double-click `install-yt-dlp.bat`
3. Double-click `install.reg`

## Detailed instructions
### Install yt-dlp
The easiest way to install yt-dlp is using winget. It comes with latest Windows 10 and Windows 11. Double-click the `install-yt-dlp.bat` file.

If this does not work check [other methods](https://github.com/yt-dlp/yt-dlp/wiki/Installation#Windows).

### Update yt-dlp
If the video download doesn't work you can update yt-dlp by opening the SHIFT + Right Click menu and clicking "Update yt-dlp to the latest version"

### Uninstall
Run `uninstall.reg` to uninstall the context menu. This will not remove yt-dlp.
