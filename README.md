# Snaff — tester releases

Tester builds of [Snaff](https://github.com/goto-software/Snaff), an AI form-filling
desktop app for Windows.

**There is no source code here.** Snaff is not open source. This repository exists
only to host tester installers, so that the download link works and so a tester's
copy can check for updates.

**These are not the real app.** They run against the development backend, so anything
you scan or save here is separate from production and may be cleared without warning.
If you just want to use Snaff, install it from
[snaff-releases](https://github.com/goto-software/snaff-releases) instead.

## Download

**[Snaff-dev-Setup.exe](https://github.com/goto-software/snaff-releases-dev/releases/latest/download/Snaff-dev-Setup.exe)** — always the newest tester build.

Windows will show a SmartScreen warning, because the installer is not yet signed.
Choose *More info* → *Run anyway*.

It installs as **Snaff dev**, beside the real Snaff rather than over it. Both can be
open at once, and they keep their settings separately.

## Updating

You don't have to. Snaff dev checks here once an hour, downloads a new build in the
background, and offers to restart when it's ready.

## Reporting a problem

Issues are turned off here. Use the **Report an issue** item in the app's tray menu,
which sends the logs along with the report.
