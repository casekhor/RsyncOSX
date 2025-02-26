## Hi there 👋

RsyncUI is a GUI on the Apple macOS platform for the command line tool [rsync](https://github.com/WayneD/rsync). It is `rsync` which executes
the synchronize data tasks. The GUI is *only* for organizing tasks, setting parameters to `rsync` and make it easier to use `rsync`.

If you find RsyncUI useful, I would appreciate it if you could consider giving me a star on the [RsyncUI repository](https://github.com/rsyncOSX/RsyncUI).
Each star serves as motivation for me to continue developing RsyncUI.


#### Install by Homebrew

RsyncUI might be installed by Homebrew or by direct Download. It is signed and notarized by Apple.

| App      | Homebrew | macOS |
| ----------- | ----------- |   ----------- |
| RsyncUI   | `brew install --cask rsyncui`    | macOS Sonoma and later |

#### External task executing rsync

Please be aware it is an external task *not controlled* by RsyncUI, which executes the command-line tool rsync. The progress and termination of the external
rsync task are monitored. The user can abort the task at any time. Please let the abort finish and cleanup properly before starting a new task.
It might take a few seconds. If not, RsyncUI might become unresponsive.

### RsyncUI (Swift, SwiftUI)

[![GitHub license](https://img.shields.io/github/license/rsyncOSX/RsyncUI)](https://github.com/rsyncOSX/RsyncUI/blob/main/Licence.MD)
![GitHub Releases](https://img.shields.io/github/downloads/rsyncosx/RsyncUI/v2.3.5/total)
![GitHub Releases](https://img.shields.io/github/downloads/rsyncosx/RsyncUI/v2.3.4/total)
[![GitHub issues](https://img.shields.io/github/issues/rsyncOSX/RsyncUI)](https://github.com/rsyncOSX/RsyncUI/issues)

**RsyncUI** is released for *macOS Sonoma and later*.

| App     | UI                  | Latest version                                                                                      |
|---------|---------------------|-----------------------------------------------------------------------------------------------------|
| RsyncUI | SwiftUI, declarativ | v2.3.5 - [26 February 2025](https://github.com/rsyncOSX/RsyncUI/releases) - in **active development** |

The [user guide](https://rsyncui.netlify.app/docs/) and [changelog](https://rsyncui.netlify.app/blog/)

![](images/rsyncui.png)

### RsyncOSX (Swift, Storyboard) - archived

[![GitHub license](https://img.shields.io/github/license/rsyncOSX/RsyncOSX_archived)](https://github.com/rsyncOSX/RsyncOSX/blob/master/Licence.MD)
![GitHub Releases](https://img.shields.io/github/downloads/rsyncosx/RsyncOSX_archived/v6.8.0/total)

**RsyncOSX** is released for *macOS Big Sur* and later.

| App        | UI | Latest version  |
| -----------  |   -------- | -------- |
| RsyncOSX   | Storyboard, imperativ   | v6.8.0 - [13 April 2023](https://github.com/rsyncOSX/RsyncOSX_archived/releases) - **not maintained**, **archived** and readonly |
