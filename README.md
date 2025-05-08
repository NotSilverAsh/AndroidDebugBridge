# 🔌 ADB Installer for Windows

<img src="https://www.gstatic.com/devrel-devsite/prod/va15d3cf2bbb0f0b76bff872a3310df731db3118331ec014ebef7ea080350285b/android/images/lockup.svg" alt="Android Developer Logo" width="300"/>

---

## 🚀 What is ADB?

**Android Debug Bridge (ADB)** is a versatile command-line tool that lets you talk to your Android device or emulator like a tech whisperer. Whether you're debugging apps, pushing files, or unlocking cool hidden features, ADB is your trusty sidekick. 🛠️📱

---

> ⚠️ **Heads Up!**  
> This installer includes the **official ADB files** directly from the [Android Developer site](https://developer.android.com/studio/releases/platform-tools). No shady stuff — just convenience, wrapped in an `.msi`.

---

## ✨ Key Features

- 📱 Install and uninstall apps  
- 📂 Push and pull files to/from your device  
- 🖥️ Access your device’s Unix shell  
- 🔍 View logs with `adb logcat`  
- 🔄 Reboot into bootloader, recovery, or straight back to Android  

For all the juicy details, check out the [official ADB guide](https://developer.android.com/studio/command-line/adb).

---

## 🛠️ Installation

### ✅ Option 1: Use the ADB Installer (.msi)

The easy-peasy way — download the `.msi`, run it, and boom 💥 you're done.  
- It auto-installs ADB and adds it to your system `PATH`.  
- No need to fumble around with ZIP files or folders.

### 🧠 Option 2: Manual Installation

1. Download the [latest platform tools](https://developer.android.com/studio#downloads).  
2. Extract the ZIP to a folder.  
3. Add that folder to your Windows `PATH`.

---

## 🧪 Usage

Open up your terminal (CMD or PowerShell) and type:

```bash
adb devices
