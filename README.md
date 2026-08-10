# KickVault — Downloads

Bulk downloader for Kick.com clips and VODs. A native Windows desktop app.

This repository holds **only the installers**. It exists so the app can check
for updates without needing any credentials — the source code lives in a
separate private repository.

---

## Download

### [⬇ Get the latest release](../../releases/latest)

| File | What it is |
|---|---|
| **KickVault-Setup.exe** | The installer. Use this one. |
| KickVault-Portable.exe | Single file, no install. For a USB stick or a machine you cannot install on. |

## Install

Double-click **KickVault-Setup.exe**.

There is no wizard and nothing to choose. It installs for your user account
only, so it **never asks for an administrator password**, and it launches itself
when it finishes. You get a KickVault shortcut on your Desktop and in the Start
Menu.

### "Windows protected your PC"

You will probably see a blue SmartScreen box the first time.

The app is not code-signed — a certificate costs a few hundred dollars a year,
and this is a personal tool. It is not a virus warning; Windows shows this for
any installer it has not seen many times before.

Click **More info**, then **Run anyway**.

## Updates

The installed app checks for new versions on its own. When one appears you get a
banner with a single **Update** button — it downloads in the background and
restarts when you say so. You never need to come back here.

There is also a **Check for updates** button in Settings.

The portable build cannot replace itself, so those users download a new copy
from this page.

## First run

Open **Settings**. The app checks for the tools it needs:

| Tool | Needed for |
|---|---|
| **ffmpeg** | Required. Joins downloaded video pieces into a playable file. |
| **ffprobe** | Required. Comes with ffmpeg. |
| yt-dlp | Optional backup downloader. |

If anything shows a red cross, click **Run setup.bat** and it installs what is
missing. Restart the app afterwards.

## Requirements

Windows 10 or 11, 64-bit.

---

## A note on use

Bulk-downloading may conflict with Kick's Terms of Service, and clips belong to
the creators who made them. This is a personal archival tool — how you use it is
your responsibility.
