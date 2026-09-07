# Galaxy Panel

A self-hosted control panel for Discord bots. A Galaxy Inc build.

Run one bot or several from one window: start and stop them, watch their logs,
change every setting, control the music, and get told when one goes offline —
from the desktop or from your phone.

## Install it

1. Download the latest `galaxy-panel-<version>.zip` from
   [Releases](../../releases/latest)
2. Unzip it anywhere
3. Double-click **`setup.cmd`**

The setup window does the rest: it builds its own Python folder, installs what
it needs, fetches ffmpeg, and takes your bot token. Bring your own bot from the
[Discord Developer Portal](https://discord.com/developers/applications) — this
panel runs it, it does not come with one.

Needs Windows and Python 3.11 or newer.

## Updating

Settings → System → Updates → **Check for updates**. It downloads the release,
checks it against the hash published beside it, and installs it. Your token,
database, settings and playlists are never touched, and every file it replaces
is kept so an update can be undone.

## What is in this repository

Downloads only. The source is private — see `LICENSE` inside the zip for what
you may do with a copy.

## Verifying a download

Each release has a `sha256.txt` beside the zip.

```powershell
Get-FileHash galaxy-panel-1.0.0.zip -Algorithm SHA256
```

---

Copyright (c) 2026 Galaxy Inc. All rights reserved.
