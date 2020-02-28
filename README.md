# About KIU Portal for macOS.

KIU Portal for macOS is an Kyungil University Student Portal System built for macOS.
Officially, portal system only supports Windows PC. (This is not an official application from school)

Previously, macOS users must install Bootcamp (Windows) or Parelles Desktop (Virtual Machine).
Both methods needs full version of Windows, which is heavy, expensive, and storage hungry.

KIUPortal for macOS is near 600MB, and you can run natviely at macOS.
It is still heavy than using portal system at Windows, but it way more lighter than using Bootcamp and Parelles.


# How deoes it work

University portal is built by "EZgen" Web builder which developed by DaegilSoft.
Therefore, you must use "EZPlatformViewer" to open website (in this case - "portal system") properly.

If you visit, main portal service page (http://portal.kiu.ac.kr/), system tries to install viewer on your sytem.
However school only provides viewer for the Windows, so Unix/Linux users are not able to use them.

Developer said this platform can be used on UNIX/LINUX/Windows, so in theory, it should support macOS.
But software company seems lazy enough to keep their website at 2004, so it is hard to expect any kind of support. 

"KIU Portal for macOS" operates portal system by faking your macOS to seem "alkie Windows"
So, using "KIU Portal for macOS" gives you exact user-interface and feautures with Windows.


# About usability 

Software was tested on Macbook Pro and other Custom-Mac Systems.
Even though, it is still buggy, and It could have some non-specified errors.

So, If you're going to do something important, It would be better select Windows PC.


# How does it work (for Developers)

"KIU Portal for macOS.app" is an script file generated with Automater on macOS.
Script calles Finder to open "ezgen.ezxml" with "KIUFramework.app".

"KIUFramework.app" is an main application which operates portal system.
It is built by WineHQ and Wineskin (Wineskin Winery on macOS)

The app has tiny Windows system taht includes minimal framework and libraries to run portal system. 

For these reasons, application has big file size than other natively-build Mac application.
But it's essential, because the application was built only for the Windows. 

Anything related to Windows enviroment, please refer to "Thanks to" section.


# Thanks to..

WineHQ (https://www.winehq.org)
Wineskin Winery (http://wineskin.urgesoftware.com/tiki-index.php?page=Downloads)
Unofficial Wineskin upate for Mojave (http://portingteam.com/topic/11037-wineskin-unofficial-update/)

