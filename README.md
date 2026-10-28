# Meridian releases

Installable Android builds (APKs) of **Meridian**, a free, ad-free weather app with no tracking:
radar, satellite clouds, a home-screen widget, and the forecast along your route. It covers the
US and Europe.

This repository holds only the release files. The source code is kept elsewhere.

## Install

1. On your Android phone (Android 8 or newer), open the
   [latest release](https://github.com/nadernik/meridian-releases/releases/latest) and download
   `meridian-latest.apk`.
2. Open the file. If Android asks, allow your browser to install apps.
3. Later versions install over this one. The app tells you when a new version is out
   (**Meridian x.y is available · Download**).

Each release lists its version. Every APK is signed with the same key, certificate SHA-256
`1752037164c68902601df2f3fe50553e98455abf8a7773ee9bcfa064a82e7f4d`.

## Files in each release

- `meridian-latest.apk`: the APK the app's Download button links to.
- `meridian-<version>.apk`: the same APK under its version number.
- `version.json`: the newest version number, which the app checks once a day.
