# Learning Equality: GSoC 2025
**Project:** Create Robust Windows App

**Mentors:** [rtibbles](https://github.com/rtibbles), [ozer550](https://github.com/ozer550)

## Summer Time

I really enjoyed the past three months. I liked the challenge of each problem—at least most of them—and I enjoyed the feeling of being part of a team. For that, I want to thank my mentors for their guidance and support! ❤️ 

## Contributions

Throughout the summer, I made several pull requests to the [kolibri-app](https://github.com/learningequality/kolibri-app) repository, each addressing a specific part of the project. Here is a summary of my contributions:

[Updated Makefile and README](https://github.com/learningequality/kolibri-app/pull/168) <br>
<dl>
<dd>This contribution focused on improving the developer experience by making the build process more reliable on Windows and clarifying the documentation.</dd>
</dl>


[Upgraded to Edge WebView2 for Web Rendering](https://github.com/learningequality/kolibri-app/pull/171) <br>
<dl>
<dd>This was an important step that resolved major UI unresponsiveness and crashes by replacing the legacy IE-based web view with the modern, Chromium-based Edge WebView2.</dd>
</dl>
    
[Separated UI and Server into Two Processes & Implemented Windows Installer](https://github.com/learningequality/kolibri-app/pull/170)
<dl>
<dd>This pull request laid the architectural foundation for the new Windows application. It separated the UI from the Kolibri server into two processes to improve stability and introduced the initial InnoSetup-based Windows installer.</dd>
</dl>
    
[Implemented System Tray Icon](https://github.com/learningequality/kolibri-app/pull/182)
<dl>
<dd>This enhanced the user experience on Windows by introducing a system tray icon for managing the application's lifecycle, providing status notifications, and allowing users to control the Kolibri service.</dd>
</dl>

[Implemented Legacy Upgrade and Data Migration](https://github.com/learningequality/kolibri-app/pull/186)
<dl>
<dd>To ensure a smooth transition for existing users, this PR introduced an automated process to migrate user data from older Kolibri installations to the new system-wide architecture and clean up the old application files.</dd>
</dl>
    
[Implemented Automated Build and Signing for Windows Installer](https://github.com/learningequality/kolibri-app/pull/188)
<dl>
<dd>This pull request added a GitHub Actions workflow to automate the building and signing of the Windows installer, streamlining the release process.</dd>
</dl>

[Added Multi-language Support to Windows Installer](https://github.com/learningequality/kolibri-app/pull/183)
<dl>
<dd>This restored multi-language support to the installer.</dd>
</dl>
