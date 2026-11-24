# Feather PDF

A fast, free PDF reader and editor for Windows, macOS, Android, iPhone and iPad. Everything happens on your own device: no account,
no cloud service, no tracking. Free to use and share, always.

**Version 2.27.0**

- Windows 7 SP1, 8.1, 10 and 11 (64-bit): [FeatherPDF-Setup-2.27.0.exe](https://raw.githubusercontent.com/akshsim1991/FeatherPDF-releases/main/FeatherPDF-Setup-2.27.0.exe) (or from the mirror: [FeatherPDF-Setup-2.27.0.exe](https://cdn.jsdelivr.net/gh/akshsim1991/FeatherPDF-releases@RELEASE/FeatherPDF-Setup-2.27.0.exe))
- macOS 11 or later (Apple silicon and Intel): [FeatherPDF-2.27.0-mac.dmg](https://raw.githubusercontent.com/akshsim1991/FeatherPDF-releases/main/FeatherPDF-2.27.0-mac.dmg) (or from the mirror: [FeatherPDF-2.27.0-mac.dmg](https://cdn.jsdelivr.net/gh/akshsim1991/FeatherPDF-releases@RELEASE/FeatherPDF-2.27.0-mac.dmg))
- Android 7 or later (phones and tablets): [FeatherPDF-2.27.0-android.apk](https://raw.githubusercontent.com/akshsim1991/FeatherPDF-releases/main/FeatherPDF-2.27.0-android.apk) (or from the mirror: [FeatherPDF-2.27.0-android.apk](https://cdn.jsdelivr.net/gh/akshsim1991/FeatherPDF-releases@RELEASE/FeatherPDF-2.27.0-android.apk)). Open the
  downloaded file; Android asks once whether your browser or file app may install apps. For an older phone that says
  the app is not compatible, take the 32-bit one: [FeatherPDF-2.27.0-android-32bit.apk](https://raw.githubusercontent.com/akshsim1991/FeatherPDF-releases/main/FeatherPDF-2.27.0-android-32bit.apk) (mirror: [FeatherPDF-2.27.0-android-32bit.apk](https://cdn.jsdelivr.net/gh/akshsim1991/FeatherPDF-releases@RELEASE/FeatherPDF-2.27.0-android-32bit.apk)). The first
  Android version reads, finds, edits text, highlights, draws, adds notes, turns and deletes pages, and saves.
- iPhone and iPad (iOS 15 or later): [FeatherPDF-2.27.0-ios.ipa](https://raw.githubusercontent.com/akshsim1991/FeatherPDF-releases/main/FeatherPDF-2.27.0-ios.ipa) (or from the mirror: [FeatherPDF-2.27.0-ios.ipa](https://cdn.jsdelivr.net/gh/akshsim1991/FeatherPDF-releases@RELEASE/FeatherPDF-2.27.0-ios.ipa)), installed from a
  Mac: see below.

Privacy: nothing is collected; see [PRIVACY.md](PRIVACY.md).

If a download does not start, your network may block raw.githubusercontent.com (some providers do at times): use the
mirror link beside it, which serves the same file (its SHA-256 is in latest.json).

Installed copies on Windows and macOS find new versions themselves (Help > Update to new version) and ask whether to
update now or later. So does the Android app (Settings > Advanced > Update to the new version, and a check when it opens):
it downloads the APK, checks it and hands it to Android's installer, which installs it over the old one, keeping your settings.
The iPhone app says when a new version is out; it is installed from the Mac the same way as the first time.

## iPhone and iPad

Feather PDF for iPhone is not in the App Store: a Mac puts it on the iPhone, signed with your own Apple ID (a free
one will do).

1. Download FeatherPDF-2.27.0-ios.ipa on the Mac, and connect the iPhone to the Mac with a cable (tap Trust on the iPhone if asked).
2. Install it with **Sideloadly** (sideloadly.io): drop the .ipa on Sideloadly, type your Apple ID, press Start.
   Or with **AltStore** (altstore.io): run AltServer on the Mac, install AltStore on the iPhone from it, then open the
   .ipa in AltStore (My Apps, +).
3. On the iPhone: Settings > General > VPN & Device Management > your Apple ID > Trust. On iOS 16 or later also
   Settings > Privacy & Security > Developer Mode > On (the iPhone restarts once).

With a free Apple ID, Apple lets such an app run for 7 days; then sign it again the same way (AltStore does it by
itself when the iPhone and Mac are on the same Wi-Fi; Sideloadly has an automatic refresh too). Installing a newer
.ipa over it keeps your settings and recent documents. Open PDFs from Files, Mail or Safari with Share > Feather PDF.
