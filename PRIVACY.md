# Privacy

XinoVault is a desktop app that runs entirely on your computer. This page says
plainly what it does with data, because you should not have to guess.

## What we collect about you

**Nothing.** XinoVault has no accounts, no telemetry, no analytics, no crash
reporting, and no servers of its own. Nothing you do in the app is sent to the
people who make it. We cannot see what you download, browse, or search.

## What stays on your computer

Everything the app knows lives in `%APPDATA%\XinoVault` on your machine:

- **Your library** — a local database of what you have downloaded, so
  duplicates are caught.
- **Settings** — download folder, filename pattern, quality preferences.
- **Platform sign-ins** — if you sign in to Kick, YouTube, Instagram, TikTok or
  Twitch inside the app, those sessions (cookies) are stored locally by the
  embedded browser, exactly as a normal browser would store them. Each platform
  has its own separate session, so signing out of one does not touch the
  others. They are used only to talk to that platform and never leave your
  machine otherwise.
- **Cookie files you supply** — if you paste or import a `cookies.txt` for a
  platform, it is saved next to the database as `<platform>-cookies.txt` and
  used only for that platform's requests. Removing it in Settings deletes it.
- **A local activity log** — the database keeps a technical record of app
  events (downloads finished, settings changed) so problems can be
  reconstructed after the fact. It is never read by the app for any other
  purpose and never leaves your machine.
- **Logs and thumbnail cache** — kept locally for troubleshooting and speed.

Deleting that folder removes all of it. Downloads themselves go to the folder
you chose (by default `Videos\XinoVault`).

## What the app connects to

XinoVault talks to other services only to do the job you asked of it:

- **The platforms you browse** (kick.com, youtube.com, twitch.tv, tiktok.com,
  instagram.com) — to list channels and download the videos you request. They
  see your IP address and, if you signed in, your session — the same as
  visiting them in a browser.
- **GitHub** — the installed app automatically checks for updates when it
  starts, by fetching a small version file from our public releases
  repository. GitHub sees an ordinary download request (your IP address), and
  nothing about you or your library is in it. Setup also downloads yt-dlp
  from GitHub.
- **gyan.dev** — during setup only, to download ffmpeg if it is missing.

No other connections are made.

## Your responsibility

XinoVault downloads publicly reachable (or your-account-reachable) media for
personal, offline use. What you download and how you use it is on you — respect
each platform's terms of service and creators' rights.

## Changes

If any of the above ever changes, this file changes in the same release, and
the changelog says so.

*Last updated: 2026-08-31.*
