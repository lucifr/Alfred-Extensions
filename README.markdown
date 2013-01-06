## README

This is a collection of alfred extensions created by [Lucifr](http://lucifr.com).

### How-to

* Download above extension by clicking the "raw" link.
* Double click the *.alfredextension file to install.
* Follow the instruction according to the extension name.

### Instructions

#### Connect to Transmit Favorite

`tran <Name of the favorite in Transmit>`

#### Subtitle

1.	Download [sscl](http://hg.splayer.org/splayerx/raw/0b9e84441210/binaries/x86_64/sscl) to ~/Downloads
2. Open Terminal.app. Run `chmod +x ~/Downloads/sscl`
3. Select the video file in Finder. Press `⌥+⌘+\` to bring up the action menu.
4. `subtitle`

You should be aware that subtitles downloaded from shooter.cn (which is a Chinese subtitle website) may be mostly in Chinese.

#### Replace Sublime Text 2 Icon

`sti <path to icns>`

`sti` without parameter will replace default icon with one by Dan Perrera, or you can use Action to bring in the <path> parameter. Change the $Path to your own permenant icon for quick replacing if you like.

#### Search Current Site

`cd <keywords>`

Search website of browser's current tab with Google's "site:xxx.com" query. 

#### NOTICE!!!

this extension supports both Safari and Google Chrome<del>, however, when both browsers are running, Safari will be considered as priority</del>. Now the extension works based on the current frontmost browser. However, it would works only when you have Google Chrome installed due to the limitation of AppleScript. If you want to use this extension with Safari only please download the "Search Current Site in Safari" extension.

#### Search Current Site in Safari

It works like "Search Current Site" extension but only works Safari. If you don't have Google Chrome installed please download this one.

### More to Come...