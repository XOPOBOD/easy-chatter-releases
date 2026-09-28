# Easy Chatter releases

Downloads and the update feed for Easy Chatter, a Windows app that writes social media replies in your own voice.

## Install

1. Open the [latest release](https://github.com/XOPOBOD/easy-chatter-releases/releases/latest) and download `Easy-Chatter-<version>-portable-x64.zip`.
2. Unzip it into a folder you can write to, like Documents or Desktop (not `Program Files`).
3. Run `Easy Chatter.exe`.

The app isn't code-signed, so the first start may show "Windows protected your PC". Click **More info**, then **Run anyway**.

## Updates

The app updates itself. It checks this repo every few minutes; when a new version is out, the round button at the bottom of the sidebar shows a download arrow. Click it to download, then click again to restart on the new version. Settings → General → About has the same button.

Your profiles, threads and settings live in `%USERPROFILE%\.easy`, outside the app folder, so updating or replacing the app never touches them.

## What's in a release

- `Easy-Chatter-<version>-portable-x64.zip`: the whole app, for new installs.
- `Easy-Chatter-<version>-app.zip`: only the app's own code, the small update for installs that are already on the same Electron version.
- `latest.json`: the version, sizes and SHA-512 checksums the app checks before installing.
