<div align="center">

# 🔐 StatusVault

### Your statuses. Your device. No ads.

**A lightweight, ad-free WhatsApp Status Saver for Android.**

Save photos and videos you've viewed in WhatsApp to your phone — with separate galleries, simple bulk selection, and a clean, modern interface.

<br/>

![Android](https://img.shields.io/badge/Platform-Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Ad Free](https://img.shields.io/badge/Ads-None-0B6E4F?style=for-the-badge)
![Privacy](https://img.shields.io/badge/Privacy-Local%20Only-14532D?style=for-the-badge)
![License](https://img.shields.io/badge/License-Choose%20a%20license-informational?style=for-the-badge)

</div>

---

## ✨ Why StatusVault?

StatusVault is designed for one job: helping you save WhatsApp statuses already available on your device — without ad clutter or unnecessary online accounts.

- **🚫 Ad-free experience** — no ads built into the app.
- **🖼️ Separate Photos and Videos tabs** — browse each media type independently.
- **⬇️ Save what you choose** — select individual items or multiple items for bulk saving.
- **👀 Preview before saving** — check a status before adding it to your collection.
- **🔒 Local-first design** — media is processed on your device; the app does not require a WhatsApp login or upload your statuses to a server.
- **📱 Made for mobile** — a modern, compact interface designed for Android screens.

> **Important:** StatusVault saves media that WhatsApp has already cached on your phone. It does not download statuses directly from WhatsApp's servers. Open/view a status in WhatsApp first, then grant StatusVault access to the relevant status folder when prompted.

## 📸 Features

| Feature | What it does |
|---|---|
| Photo gallery | Browse available image statuses in a dedicated section |
| Video gallery | Browse available video statuses in a separate section |
| Preview | Preview supported media before saving |
| Multi-select | Select several items and save them together |
| Gallery saving | Save copies into StatusVault folders on your device |
| Folder picker | Grant access to the specific folder instead of broad storage access |
| No account required | No StatusVault account or WhatsApp credentials needed |

## 🚀 Getting started

1. Open WhatsApp and view the photo or video statuses you want to save.
2. Open StatusVault.
3. Choose the WhatsApp status/media folder when the app asks you to select it. On some Android versions, this folder may be hidden or unavailable through the system picker.
4. Browse the **Photos** or **Videos** section.
5. Preview and select the statuses you want.
6. Tap **Save** to copy selected media to your device.

### Where are saved files stored?

Saved items are placed in the StatusVault folders configured by the app, typically under your device's public `Pictures/StatusVault` and `Movies/StatusVault` locations.

## 📲 Install

### Option A — Download a release APK

1. Open the repository's **Releases** section.
2. Download the APK asset attached to the latest release.
3. Open the downloaded APK on your Android device and follow the installation prompts.

Only download APKs from a source you trust. Android may ask you to allow installation from your browser or file manager.

### Option B — Build with GitHub Actions

This project can be built using GitHub Actions without installing Android Studio locally.

1. Fork or clone this repository.
2. Ensure the Android project files are committed to the repository.
3. Open **Actions** and run the **Build StatusVault APK** workflow.
4. When the workflow succeeds, open the run summary.
5. Download the `StatusVault-debug-apk` artifact and extract the APK from the downloaded ZIP.

> The Actions artifact is a build output, not a signed Play Store release. For public distribution, configure a secure release-signing process and publish APKs through GitHub Releases.

## 🛡️ Privacy & permissions

StatusVault is intended for local, personal use.

- **No ads:** the app is designed without advertising.
- **No WhatsApp login:** never enter or share your WhatsApp credentials with a status-saver app.
- **Local media handling:** the app is designed to save media on your device rather than upload it to a third-party service.
- **Scoped folder access:** Android's folder picker lets you grant access to the relevant folder.

Permission behavior can vary by Android version and by how WhatsApp stores its media. Review the app's requested permissions and source code before installing builds from anyone else.

## ⚠️ Notes & limitations

- Statuses may disappear from WhatsApp's cache after a period of time. Save items while they are still available.
- Some Android versions restrict access to hidden `.Statuses` folders. StatusVault can only show items that Android allows it to access.
- StatusVault is an independent utility and is **not affiliated with, endorsed by, or sponsored by WhatsApp or Meta**.
- Please respect other people's privacy and obtain permission before redistributing their photos or videos.
- WhatsApp is a trademark of Meta Platforms, Inc.

## 🧰 Build details

The repository's GitHub Actions workflow builds a debug APK using the Android SDK and Gradle. Build requirements and commands are defined in the workflow and Android project files.

For development, open the Android project in Android Studio or use the included GitHub Actions workflow to build in the cloud.

## 🤝 Contributing

Suggestions, bug reports, and pull requests are welcome.

When reporting an issue, include:
- Android version and device model
- The step you were performing
- What you expected to happen
- What actually happened
- Relevant screenshots or build logs (remove personal information first)

## 📄 License

A license has not yet been specified. Before redistributing or accepting contributions, add a `LICENSE` file and update this section with the chosen license.

---

<div align="center">

**StatusVault — save simply, browse beautifully, stay ad-free.** 💚

</div>
