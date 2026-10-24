# Song Studio: releases

This repository holds the installers for Song Studio for macOS. Song Studio turns lyrics into a Suno song, a karaoke video and a lead sheet, with coding agents doing the work alongside you. It runs on Apple Silicon Macs with macOS 13 or later.

The app updates itself. When a new version is out, it downloads it, checks its signature and installs it when you quit the app.

## First install

1. Under **Releases**, download the newest `SongStudio-<version>.zip`.
2. Unzip it and drag **Song Studio** into **Applications**, or into `~/Applications`.
3. Open the app. macOS blocks it the first time, because the app is not signed by Apple. To allow it:
   1. Go to **System Settings → Privacy & Security**.
   2. Scroll down and click **Open Anyway**.
   3. Open the app again.
4. In the app, open **Settings → Machine check**. It lists anything still missing, such as ffmpeg, uv, MuseScore or an image API key.

You can switch the interface between English and Vietnamese under **Settings → Language**.

## Updates

You don't need to do anything. The app checks for updates every hour and installs the new version when you quit. To update right away, choose **Song Studio → Check for Updates…**.

_Song Studio used to be called Quê Hương Studio. Older copies update themselves to the new name._
