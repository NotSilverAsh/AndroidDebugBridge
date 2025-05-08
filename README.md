# 🔌 ADB Installer for Windows

<img src="https://www.gstatic.com/devrel-devsite/prod/va15d3cf2bbb0f0b76bff872a3310df731db3118331ec014ebef7ea080350285b/android/images/lockup.svg" alt="Android Developer Logo" width="300"/>

## 🚀 What is ADB?

Android Debug Bridge (ADB) is a versatile command-line tool that lets you communicate with an Android device or emulator. Whether you're a developer debugging apps or a power user tweaking your device, ADB is your go-to tool.

**Key Features:**
- 📱 Install and uninstall apps
- 📂 Push and pull files to/from your device
- 🛠️ Access Unix shell on your device
- 🔍 View device logs with `logcat`
- 🔄 Reboot devices into various modes (bootloader, recovery, etc.)

For official documentation and more details, check out the [Android Developers ADB Guide](https://developer.android.com/studio/command-line/adb).

## 🛠️ Installation

### Option 1: Use the ADB Installer (.msi)

To make your life easier, we've bundled ADB into a convenient Windows installer. Just download and run the `.msi` file, and you're good to go!

### Option 2: Manual Installation

If you prefer to install ADB manually:

1. Download the latest SDK Platform Tools from the [Android Developer website](https://developer.android.com/studio#downloads).
2. Extract the ZIP file to a location on your computer.
3. Add the extracted folder to your system's PATH environment variable to run ADB from any command prompt.

## 🧪 Usage

Once installed, open a command prompt and type:

```bash
adb devices
