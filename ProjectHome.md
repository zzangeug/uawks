[![](http://uawks.googlecode.com/svn/trunk/docs/screenshots/NotificationIcon.png)](http://code.google.com/p/uawks)

# Update: August 3, 2010 #

UAWKS is developed completely on donated time, which isn't always plentiful these days. UAWKS will always be free, but any donations would be appreciated! In particular, donations will contribute towards fixing the issues on the [Issues Page](http://code.google.com/p/uawks/issues/list). Thanks!

[![](https://www.paypal.com/en_US/i/btn/btn_donate_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=QKPH4YVKNN8MG&lc=US&item_name=UAWKS&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donate_LG%2egif%3aNonHosted)

# Update: May 24, 2010 #

  * Brian is _finally_ working on UAWKS again

  * Brian _finally_ has Windows 7

  * The source code repository is moving from Subversion (svn) to Mercurial (hg)

  * The source code repository will include Brian's build scripts, so to install/run from the repository you'll need [AutoHotkey](http://www.autohotkey.com/), [Python](http://www.python.org/), and [NSIS](http://nsis.sourceforge.net/Main_Page); the reason for the build scripts is to automate things like updating the file headers with the version number/date, etc

  * There will still be a source release that doesn't require running the build scripts

# UAWKS needs your help! #

**The [bug tracker](http://code.google.com/p/uawks/issues/list) is the best way to report a problem, but due to repeated requests, you can contact Brian at [uawks.contact@gmail.com](mailto:uawks.contact@gmail.com)**

**Also -- motivated developers are invited to join the project and contribute needed patches/updates! Please [contact us](mailto:uawks.contact@gmail.com)!**

## UAWKS 2008.09.17 Released ##

Bug fix release. Most users should upgrade. Get it in the downloads section or in the downloads bar to the right. Please report issues and suggestions using the bug tracker.

  * Vista compatibility update: Added option to disable volume overlays and enable use of normal media keys.
  * Fixed bug where "RAlt" literal was being typed instead of actual right alt key.
  * Experimental bug fix for some of the AltGr problems (but not all, yet).

## Overview ##

Unofficial Apple Wireless Keyboard Support (UAWKS) is a small package that allows Windows users to make full use of Apple's uber-sexy bluetooth keyboard. Most importantly, it provides support for essential keys that don't work out of the box:

| **Forward Delete**              | Fn + Delete                |
|:--------------------------------|:---------------------------|
| **Home, End, Page Up and Down** | Fn + Arrow Keys            |
| **Media and volume control**    | Fn + F7-F12                |
| **Print Screen**                | Fn + F3                    |
| **CTRL-ALT-DEL**                | Control + Alt + Delete     |
| **Eject**                       | Eject                      |

## Additional Features ##

  * **Translucent volume overlay.**

  * **Use Command (Apple) keys as Control keys (optional).** Use Command-C for copy, Command-V for paste, etc. Toggle in the UAWKS notification icon (tray icon) menu.

  * **Use media/volume keys without holding down Fn (optional).** As in OS X, you can choose to have the media and volume controls take effect with or without holding Fn (either way, you can still use your F7-12 keys normally by doing the opposite).

  * **Use Control-` as Shift-Control-Tab (optional).** Many tabbed applications on Windows use Control-Tab to cycle forward, and Shift-Control-Tab to cycle backwards. Shift-Control-Tab is really awkward on the AWK, so this rebinds it to Control-Backquote.

  * **Use Right Option key as an extra Fn key (optional).** If you don't need two option keys, this makes it easier to hit forward delete, home, etc.

  * **Use left control as a Windows key (optional).** This is helpful if you've rebound your command keys to act like control keys, as above. Please note that the Windows key is almost completely useless, and has been deprecated by a jury of your peers.

  * **Use caps lock as an extra control key (optional).** Apparently, before computers were even invented, an Emacs user somewhere attained the ability to reason introspectively. He noticed that he wasn't using Caps Lock for anything except posting flames to Usenet. Okay, just kidding, but it does turn out that rebinding Caps Lock as another control key makes it that much more comfortable to hit C-u 3 C-x 5 2.

## Source ##

To run UAWKS from source, you'll need [AutoHotkey](http://www.autohotkey.com/). After it's installed, run UAWKS.ahk. If you want to add custom AHK bindings, User Keys.ahk exists solely for this purpose (it's just an empty file included at the end of UAWKS.ahk). See the [AHK Tutorial](http://www.autohotkey.com/docs/Tutorial.htm) to get started.

## Acknowledgements ##

UAWKS is implemented with [AutoHotkey](http://www.autohotkey.com/). The code which interfaces with bluetooth HID devices was created by [Micha](http://www.autohotkey.net/~Micha/HIDsupport/Autohotkey.html). Code which adapts this for use with the Apple Wireless Keyboard was originally created by [Veil](http://www.autohotkey.com/forum/topic6367-75.html) (also see his post [here](http://yotz.eu/fnkey/) for more information about using Micha's DLL with bluetooth devices).

Enjoy!