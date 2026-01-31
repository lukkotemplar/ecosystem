# WINDOWS 95
This document serves as a guide to configure the other system, Windows 95.
## SUMMARY
Now, this isn't actually Windows 95. It's Linux, more specifically Xubuntu.
Thanks to the Chicago95 tweak, it's possible to do an almost 1:1 replica of Windows 95 on XFCE. However, it only works in Ubuntu and Arch related systems. For this guide, we will have Xubuntu as reference.
I will explain first the behaviour of the system, and later it's appearance.
## BEHAVIOUR
### WHAT THIS SYSTEM IS FOR
This system is intended for browsing, coding, playing games and other programs (like mailing), like 30 years ago. It's a gold mine for nostalgics who want to relive the good ol' days of Windows.
### BROWSING
The browser used will be PaleMoon, a fork of Linux. I choosed this browser because of it's 2000s appearance and its compatibility with modern websites.
The search engine will be DuckDuckGo, with the Home Page being the blank page.
As for the toolbar, it will have the following elements (starting from the right):
- Back and Forward Buttons
- Reload Page Button
- Home Page Button
- Search box
- Downloads button
- Add-ons button (like Greasemonkey for old YT)
For old YT, I will use V3 and StarTube, with GreaseMonkey script manager. YT will have a 2015 look, as StarTube has some problems loading older layouts.
Some pages have issues, but in general the browser can be very well used.
### PLAYING
When playing, there are two types of games: Steam Games and Flash Games.
#### STEAM GAMES
Most games in my library run very well. However, there are some games that present issues (like FNAF).
#### FLASH GAMES
As for the Flash games, I will use Adobe Flash 32, which runs as a script. I haven't tested it much, but Flipline Studios games should work well.
### CODING
Coding will be done on neovim, with rather a minimal setup. However, there may be some contexts in which the Hyprland system will work better.
Examples of languages that have full support on W95:
- Python
- C
- C++
Examples of languages that may require the other system:
- Java
- Flutter
- HTML and CSS (I know it's not a language)
### OTHER PROGRAMS
#### MAILING
Sylpheed will be used. However, the only configurable e-mail is the personal, as the university one has no compatibility with old-styled mail clients. For the latter, the browser will be used.
To configure the mail, I will need a low-security password, configured from the google account (Thanks google :/)
At the moment, the default appearance and configuration is good. If anything is to be changed, it will be documented here
#### TERMINAL
The terminal used will be the XFCE one, as it can be very faithful to the Windows one. If any other terminal is better, I will use it instead.
The configuration is as follows.
GENERAL
- Title: MS-DOS Prompt, with Dynamically-set title not displayed
- Cursor shape: Underline, with blinking enabled
APPEARANCE
- Font: Less Perfect DOS VGA Regular, size 12
- Background: None
- Colors: Chicago95 Preset
The terminal's behaviour will be very, very similar to the MS-DOS one, with commands, displaying and spacing changed to match that one.
#### TAKING NOTES
Neovim will be used. It's conf files will be uploaded to GitHub.
#### VIDEO PLAYING
TBD
#### AUDIO PLAYING
TBD
## APPEARANCE
As for the appearance, I will try to stick to the original Windows.
### DESKTOP
The desktop will have only the following icons:
- The internet (Internet)
- Inbox (Mail)
- My Computer (File Manager)
- Trash (Recycle Bin)
### START MENU
The start menu will be Windows 95-styled (it should display at the left "Windows 95"), and it should have the following categories:
- Favourites: The internet, Inbox, My Computer, MS-DOS Prompt, Help and Run...
- Games: Steam and Flash Games
It will also have icons for Settings, Shut Down and Suspend
### WINDOWS BAR
The bar will have the following elements in order:
- Whisker Menu (Start menu, see above)
- Handle Separator
- Icon for Web Browser
- Icon for Show Desktop
- Handle Separator
- Window Buttons
- Transparent expanded Separator
- PulseAudio Plugin
- Battery Plugin
- Clock
It will also have the following settings
- Row size: 28px
- Fixed icon size: 17px
## ADITIONAL SETTINGS
- Display: 1.75 or 1.5
- DPI: 99
- Font: Helvetica, size 9
- Window Manager style: Chicago95, Helvetica Bold 9
## CONCLUSION
This is the complete additional setup of the Windows 95 system, after doing all the configurations from the official repo of Chicago95.
Any changes to the system will be documented here.
