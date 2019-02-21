# KIUPortal-Engine

Thanks for using KIUPortal for macOS.
KIUPortal for macOS is built by Wine (the Linux/Unix Windows Execution Libraries) and it's wrapped by Wineskin.

However, this application is not official, and it's also very unstable than original Windows verison.
Application includes essential Windows frameworks and libraries to operate software "alike Windows"

This is what happens to your mac when you start your portal.

1) You stat "KIU Portal.app" which created by Automater (which is deafualt application on macOS)
2) Automater calls "portal.ezxml" with "KIUFramework.app"
3) "KIUFramework.app" is built by Wineskin Winery and it includes Window's frameworks and libraries.
4) When "KIUFramework.app" starts up, application calls essential Windows framework and libraris to make system alike Windows.
5) After essential stuffs load finished, EzPlatformViewer launches, and call "portal.ezxml" to start actual portal system.

For these reasons, application has big file size (not bigger thant Bootcamp neither Parelles Desktop)
But it's essential thing, because the application was built only for the Windows. 

Software was built in Wineskin Winery and tested on Macbook Pro and other Custom-Mac Systems.

