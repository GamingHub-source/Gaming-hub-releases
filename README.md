<div align="center">

# 🎮 Gaming Hub

### Your games. One clean desktop launcher.

**A lightweight Windows gaming dashboard for discovering, organizing, and launching your favorite games.**

[![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D4?style=for-the-badge&logo=windows11&logoColor=white)](https://github.com/GamingHub-source/Gaming-hub-releases/releases)
![Version](https://img.shields.io/badge/Version-0.8.0-12B8CF?style=for-the-badge)
![Price](https://img.shields.io/badge/Price-Free-24A86A?style=for-the-badge)
![Source](https://img.shields.io/badge/Source-Private-343A46?style=for-the-badge)

**[⬇️ Download Gaming Hub](https://github.com/GamingHub-source/Gaming-hub-releases/releases/latest)** · **[📦 All Releases](https://github.com/GamingHub-source/Gaming-hub-releases/releases)** · **[🐛 Report an Issue](https://github.com/GamingHub-source/Gaming-hub-releases/issues)**

</div>

---

## ✨ What is Gaming Hub?

Gaming Hub brings your installed games together in a customizable Windows launcher. Select what belongs on your dashboard, assign a Steam account reminder to each game, and launch games without hunting through multiple libraries.

No Gaming Hub account is required, and the app is free to use.

## 🚀 Features

| Feature | What it does |
|:--|:--|
| 🧭 **Game discovery** | Detects installed Steam games across multiple library drives; includes Epic Games discovery support. |
| 🎮 **Custom library** | Pick the games you want to see on your main dashboard. |
| ➕ **Add your own games** | Add local `.exe` files and Windows `.lnk` shortcuts, including launchers like TLauncher. |
| 🖼️ **Custom covers** | Personalize your library with your own game artwork. |
| 👤 **Steam account labels** | Associate games with a saved Steam account choice for reference. |
| 🖥️ **Desktop mode** | Optional desktop-integrated layout. |
| 📌 **System tray** | Minimize the launcher and restore it when needed. |
| 🔄 **Update controls** | Check, download, and apply available releases in supported installed builds. |
| 🧰 **Diagnostics** | Access local diagnostic logs when troubleshooting. |

> **Heads up:** Steam account labels are informational only. Gaming Hub **does not** automatically switch Steam accounts, store Steam passwords, or bypass authentication. EA App, Ubisoft Connect and Battle.net discovery is experimental; Epic Games discovery has not yet been confirmed in real-world testing.

## 📥 Download & install

1. Open the **[Releases page](https://github.com/GamingHub-source/Gaming-hub-releases/releases)**.
2. Choose the newest **published** version.
3. Under **Assets**, download the Windows installer (`.exe`). Do not download `Source code (zip)` — this repository is for distribution only.
4. Run the installer and follow the on-screen steps.
5. Launch **Gaming Hub** from the Start Menu, choose your games, and click **Accept**.

**Requirements:** Windows 10 or Windows 11 (64-bit). Steam/Epic Games or other supported launchers must be installed to use their respective games. Node.js and VS Code are **not** required for the installed application.

> ⚠️ **Early release notice:** Versions in the 0.x series are in testing. Windows SmartScreen may warn about the installer because the current build is not code-signed. Only download installers from the official GitHub Releases page, and verify the publisher/source before running software.

## 🕹️ How it works

```text
Launch Gaming Hub
        ↓
Scan installed games / add a local game
        ↓
Choose which games appear on your dashboard
        ↓
Press Accept
        ↓
Launch your favorite game
```

You can revisit the library whenever you want to add or remove dashboard entries.

## 🔄 Updates

On supported **installed** Windows builds:

1. Open **Settings** → **Check for updates**.
2. If a newer published release is available, select **Download update**.
3. When the download is ready, choose **Restart to update**.

Updates require a valid published release with updater metadata. Portable builds and development runs are not guaranteed to support automatic installation. If an update check fails, check that a published release exists and try again later.

## 🔒 Privacy & security

- No Gaming Hub login or subscription required.
- Game preferences are stored locally on your PC.
- Steam account assignments are only labels; Gaming Hub does not collect your Steam password.
- Diagnostic logs remain local unless you choose to share them.
- Gaming Hub is an independent project and **is not affiliated with or endorsed by Valve, Steam, Epic Games, or other game publishers**.

## 🐛 Bugs & feedback

Found a problem or have an idea? **[Open an issue](https://github.com/GamingHub-source/Gaming-hub-releases/issues)** and include:

- Your Windows version.
- Your Gaming Hub version.
- Steps to reproduce the problem.
- The exact error message, if available.

Please **remove personal information, access tokens, and account details** before attaching logs or screenshots.

## 🗺️ Roadmap

- [x] Steam library discovery
- [x] Manual `.exe` / `.lnk` game support
- [x] Custom game covers
- [x] Steam account selection labels
- [x] Windows installer workflow
- [ ] Validate update installation across versions
- [ ] Improve EA / Ubisoft / Battle.net discovery
- [ ] Complete clean-PC compatibility testing
- [ ] Code-sign public Windows installers

## 📄 License & distribution

**Freeware · Proprietary source**

Gaming Hub is free to download and use. Its source code is privately maintained and is not licensed as open source. Redistribution or modification rights are not granted by this README. A separate end-user license may be published before broad release.

---

<div align="center">

Made for a cleaner gaming desktop. 🎮

**[⬆ Back to top](#-gaming-hub)**

</div>
