# evergreen-pakages
Provides an installer and auto-updater for your repo

## Why?

When using a repo as a developer, having git installed is really simple to just `git pull` and receive the latest version of the code.

But once compiled and packaged to distribute to non-developers, we're all the sudden back to the days of downloading files and updating manually.

## How is evergreen-pakages solving it?

The idea is that this package allows you to create an "installer" and a "starter".

The **installer** will download and unpackage a project in the user's `~/.evergreen-pakages` folder.

The **starter** will boot the project, check for updates and re-install the project. In the next reboot of the app the user will run the newer version.

----

Let's see if we can pull it off! 🙂
