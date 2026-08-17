# Active Time Tracker — downloads

Installer downloads and update checks for **Active Time Tracker (TimeCalc)**.
The application source is maintained in a private repository.

## Install
Download the latest `ActiveTimeTracker-Setup-x.y.z.exe` from
[Releases](../../releases/latest) and run it. No admin rights required, and no
Python installation needed.

The overlay appears in the top-right corner. Right-click it for the dashboard,
colour themes, task notes and reports.

## Updating
The app checks here automatically and shows an **i** badge in the overlay when a
new version is available. Click the badge to download it.

## What it does
- Tracks genuinely active time, excluding sleep, the lock screen and idle periods
- Records which applications and windows you used, and captures on-screen text
  locally using Windows' offline OCR
- Detects calls and screen sharing, so meetings count even while you work in
  another window
- Optionally turns the day into a described, categorised task list for
  timesheets, using an Azure AI Foundry project you configure during setup
- Serves a local dashboard at `http://127.0.0.1:7788/`

All data stays on your machine, in an `ActivityData` folder beside the app.
