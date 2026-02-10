# Eden Experimental Fork

<img width="1024" height="1024" alt="eden trigger" src="https://github.com/user-attachments/assets/ecb1d65d-f0d2-457f-887f-84abf4b1b5e8" />


## Overview

This is an **experimental fork** of the Eden Emulator Project, designed to test and implement various features and optimizations. This fork focuses on enhancing user experience through additional performance monitoring and memory management features.

## 🚀 New Features

### Memory Management
- **Memory Flush Option**: Added a toggle to enable/disable memory flush functionality during gameplay
  - **Location**: Settings → System → App Settings → Enable Memory Flush
  - **Purpose**: Clear app memory and caches for better performance
  - **Usage**: When enabled, shows a memory flush button during gameplay

### Performance Monitoring
- **Phone Temperature Display**: Added real-time phone temperature monitoring
  - **Location**: Settings → Performance Stats → Show Phone Temperature
  - **Purpose**: Monitor device thermal state during emulation
  - **Display**: Shows current phone temperature in the performance overlay

## 📱 Installation

### APK Variants Available

1. **Standard Edition** (`mainline`)
   - App Name: "Eden"
   - Package: `dev.eden.eden_emulator`
   - Architecture: ARM64

2. **Optimized Edition** (`genshinSpoof`)
   - App Name: "Eden Optimized"
   - Package: `com.miHoYo.Yuanshen`
   - Architecture: ARM64

3. **Legacy Edition** (`legacy`)
   - App Name: "Eden Legacy"
   - Package: `dev.legacy.eden_emulator`
   - Architecture: ARM64

4. **ChromeOS Edition** (`chromeOS`)
   - App Name: "Eden ChromeOS"
   - Package: `dev.eden.eden_emulator`
   - Architecture: x86_64

### Installation Steps
1. Download the appropriate APK variant for your device
2. Enable "Install from unknown sources" in Android settings
3. Install the APK
4. Launch the app and follow the setup wizard

## ⚙️ Configuration

### Memory Flush Setup
1. Open **Settings**
2. Navigate to **System** section
3. Find **App Settings** category
4. Toggle **"Enable Memory Flush"**
5. The memory flush button will appear during gameplay

### Temperature Monitoring Setup
1. Open **Settings**
2. Navigate to **Performance Stats** section
3. Toggle **"Show Phone Temperature"**
4. Temperature will display in the performance overlay during gameplay

## 🔧 Build Instructions

### Prerequisites
- Android Studio (latest version)
- NDK/CMake
- Git
- Eden submodule

### Building All Variants
```bash
# Build all variants at once
./gradlew assembleRelease assembleDebug

# Or build specific variants
./gradlew assembleMainlineRelease
./gradlew assembleGenshinSpoofRelease
./gradlew assembleLegacyRelease
./gradlew assembleChromeOSRelease
```

### Output Locations
All APKs are generated in:
```
app/build/outputs/apk/
├── mainline/release/
├── genshinSpoof/release/
├── legacy/release/
└── chromeOS/release/
```

## 🧪 Experimental Features

This fork includes experimental features that may:
- Enhance performance on certain devices
- Provide additional system monitoring
- Offer new user interaction methods

**Note**: These features are experimental and may not be stable in all configurations.

## 🐛 Bug Reports

Since this is an experimental fork, please report issues with:
1. Device model and Android version
2. APK variant used
3. Steps to reproduce the issue
4. Log files if available

## ⚠️ Disclaimer

This is an **unofficial experimental fork** of Eden Emulator. It is not affiliated with the official Eden Emulator Project. Use at your own risk.

## 📄 License

This project maintains the same license as the original Eden Emulator Project (GPL-3.0-or-later).

## 🔗 Links

- **Original Eden Project**: https://eden-emu.dev
- **Source Code**: https://git.eden-emu.dev/eden-emu
- **Discord**: https://discord.gg/HstXbPch7X

---

## 📋 Version Information

- **Fork Version**: Experimental v1.0
- **Based on**: Eden Emulator Project
- **Target API**: 36 (Android 14)
- **Min API**: 24 (Android 7.0)

---

**Thank you for trying this experimental fork!**

<img width="1024" height="1024" alt="eden trigger icon" src="https://github.com/user-attachments/assets/c8820d64-a07a-4985-988c-7dfb63dd97e7" />

