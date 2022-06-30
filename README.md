# Windows-11-Inconsistencies
**I've compiled this list of inconsistencies from these two videos to see which ones have been updated and which haven't. With the Windows Insider beta channel for 22H2 on 6/29/2022, this is what I have found.**

## Windows 10 Remnants
1) Calculator - updated to Windows 11 ✔
2) Camera - unchanged from Windows 10 ❌
3) Mail - unchanged from Windows 10 ❌
4) LogonUI Network Flyout - unchanged from Windows 10 ❌
5) On-Screen Keyboard - unchanged from Windows 10 ❌
6) Magnifier - unchanged from Windows 10 ❌
7) Registry Editor Product Name - unchanged from Windows 10 (seriously?) ❌

**Score: 1/7**

## Windows 8/8.1 Remnants
1) LogonUI Ease of Access Flyout - updated to Windows 11 ✔
2) BSOD - essentially unchanged since Windows 8 ❌
3) Task Manager - updated to Windows 11 ✔
4) Volume & Brightness Rockers - updated to Windows 11 ✔
5) Unknown File Type Dialogue - unchanged since Windows 8 ❌
6) This App Can't Run on Your PC Dialog - unchanged since Windows 8 ❌
7) AutoPlay Dialog - unchanged since Windows 8 ❌
8) Spinning Loading Dots - changed to Windows 10X loading wheel in only some areas, half credit (also modifiable system-wide with a registry tweak) ✔❌

**Score: 3.5/8**

## Windows 7 Remnants
1) Many Options Panels - unchanged from Windows 7 ❌
2) Scan and Fix Dialog - unchanged since Windows 7 ❌
3) USB Safe Removel - unchanged since Windows 7 ❌
4) Control Panel - unchanged since Windows 7, functionality only removed and broken ❌
5) Remote Desktop Connection - unchanged since Windows 7 ❌
6) Paint - updated to Windows 11 ✔
7) WordPad - unchanged since Windows 7 ❌
8) MTP File Transfer Progress Bar - unchanged since Windows 7 ❌

**Score: 1/8**

## Windows Vista Remnants
1) Windows Mobility Center - unchanged since Windows Vista ❌
2) User Contacts Folder - unchanged since Windows Vista ❌
3) Control Panel Sound Panel - unchanged since Windows Vista ❌
4) User Account Control Settings - unchanged since Windows Vista ❌
5) Device Manager - unchanged since Windows Vista ❌
6) Windows Fax and Scan - unchanged since Windows Vista ❌
7) Shutdown Dialog Engine - back-end unchanged since Windows Vista but front-end is different, half credit ✔❌
8) No GUI Boot - unchanged since Windows Vista (no proof currently because nobody could trigger it) ❌

BONUS 1) "In MCC, the "multi document interface" is used (basically the Program Manager interface which let you have multiple sub windows inside one parent window), even though there's very little point to it. The child windows also use the Windows Aero Basic theme," quote mjdxp ❌
BONUS 2) Task Scheduler Windows Version Configuration Box - default is still "Windows Vista™, Windows Server™ 2008" ❌
**Score: 0.5/10"

## Windows XP Remnants
1) ZIP Archive Explorer - essentially unchanged since Windows XP, updated exclusively to make compatible with newer explorer ❌
2) Phone and Modem - unchanged since Windows XP ❌
3) WordPad Dialogs - unchanged since Windows XP ❌
4) Character Map - unchanged since Windows XP ❌
5) Security Alert - unchanged since Windows XP ❌
6) "Driver (INF) Setup" - unchanged since Windows XP ❌
7) Task Scheduler Account Information Dialog - unchanged since Windows XP ❌

BONUS) "In Windows Server 2016 (and probably all other versions of Windows Server since then), if you dive deep enough into the Group Policy Editor, you can find an interface which is completely unchanged from Windows XP. It looks exactly like an XP control panel window," quote mjdxp ❌
**Score: 0/8**

## Windows 2000 Remnants
1) Desktop - core unchanged since Windows 2000 ❌
2) MMC & .msc files - essentially unchanged since Windows 2000 ❌
3) winver - unchanged since Windows 2000 (and broken even more in Windows 10) ❌
4) Properties Menu - essentially unchanged since Windows 2000 ❌

**Score: 0/4**

In-between) Notepad - updated to Windows 11 ✔
**Score: 1/1**

## Windows 98 Remnants
1) Offline Web Pages - useless now, left since Windows 98 ❌
2) Disk Cleanup - essentially unchanged since Windows 98 ❌
3) Internet Properties - essentially unchanged since Windows 98 ❌
4) Run - unchanged since Windows 98 ❌

**Score: 0/4**

## Windows 95 Remnants
1) dwm.exe - built upon since Windows 95 (classic theme is accessible with effort) previous shell layers not removed ❌
2) Task Scheduler Account Information Dialog Help Button (and probably other help buttons too) - unchanged since Windows 95 ❌
3) "Read-only" Argument in File Properties - left since Windows 95, basically useless due to deprecation of floppy drives ❌
4) Screensavers - unchanged since Windows 95 ❌

**Score: 0/4**

## Windows 3.1 Remnants
1) ODBC Data Source - unchanged since Windows 3.1 ❌
2) pifmgr.dll and moricons.dll (ancient icon libraries) - left since Windows 3.1 ❌

BONUS 1) cmd Layout Properties Window Preview Minimize and Maximize Buttons - unchanged since Windows 3.1 ❌
BONUS 2) "Also, not sure if this is from 3.x exactly, but there's the dialer.exe program for making calls on your you know... telephone line," quote astra3 ❌
BONUS 3) "I got an error message once in Win7 when I was running some programs for Windows 1.x or 2.x... it went something like "This program was made for a version of Windows before 3.1, are you sure you want to run it?" The same message appears in 3.1 when you try to do something like that. Now, I'm not sure if it's accessible still, since 64bit Windows can't run old 16bit apps, but I'd bet you it's still in there in the code. And there are probably more," quote Luka Marinov ❌
**Score: 0/5**

**Overall Score: 7/60**

The fact that there are still remnants that go all the way back to Windows 3.1 is baffling. It's crazy how lazy Microsoft has gotten when it comes to updating these features. It seems like the older they get, the less likely Microsoft is to actually update them. I have my doubts that the Windows 3.1 remnants will ever receive an update. If Microsoft dedicated an entire feature update to fixing these ancient elements of their bloated operating system, I would be extremely happy as it's long overdue. They're clearly leaving these so people just get used to them and forget that they were ever outdated.

## References/Resources
"The State of Windows" by Enderman (https://youtu.be/dePr2PPT898)

"The old Secrets of Windows 11" by Enderman (https://youtu.be/2GBs1GapIvw)
