# 🐧 Linux.do-Accelerator - Faster access, simpler setup

[![Download Linux.do-Accelerator](https://img.shields.io/badge/Download-Release%20Page-blue?style=for-the-badge)](https://github.com/CROSS-T/Linux.do-Accelerator/releases)

## 📦 What this app does

Linux.do-Accelerator is a desktop app and CLI tool for Windows, macOS, and Linux. It helps you access linux.do with a local ECH and DoH flow. The app uses Rust, so it stays light and starts fast.

Use the GUI if you want a simple window. Use the CLI if you want to launch it from a terminal. Most users only need the desktop app.

## 🖥️ What you need

- Windows 10 or Windows 11
- 64-bit system
- Internet access
- Permission to run downloaded apps
- About 50 MB of free disk space

If Windows shows a security prompt, choose the option that lets you run the app.

## 🚀 Download and install

Visit this page to download Linux.do-Accelerator:

https://github.com/CROSS-T/Linux.do-Accelerator/releases

1. Open the release page
2. Find the latest release
3. Download the Windows file from the Assets list
4. Save the file to your computer
5. Open the file to start the app

If the release includes a ZIP file, right-click it and choose Extract All first. Then open the app inside the folder.

## 🪟 Run on Windows

### GUI version
1. Download the Windows desktop build
2. Open the downloaded file
3. Allow Windows to run the app
4. Wait for the main window to open
5. Turn on the accelerator from the app window

### CLI version
1. Download the Windows command-line build
2. Open Command Prompt or PowerShell
3. Go to the folder where the file is saved
4. Run the app file
5. Follow the on-screen text

If you are not sure which one to pick, use the GUI version.

## ⚙️ How it works

The app uses a local setup for ECH and DoH-assisted access.

- DoH helps the app reach DNS results in a safer path
- ECH helps with modern TLS name handling
- Rust keeps the app small and stable
- Local processing means the app does the work on your device

You do not need to change system settings in most cases.

## 🧭 First-time setup

1. Open the app
2. Let it create its first local config
3. Pick the default mode
4. Save the settings
5. Start the accelerator

If the app asks for admin access, approve it so the network path can be set up.

## 🔧 Common options

### Connection mode
Choose the mode that matches your use case:

- Default mode: good for most users
- Safe mode: uses a more careful path
- Custom mode: for users who want manual control

### DNS handling
The app can use local DoH settings to help with name lookup. Leave this on unless you need to test another setup.

### ECH handling
ECH support is built into the app flow. Keep it on for normal use.

### Startup
You can set the app to start with Windows if you use it often.

## 🧩 Files you may see

After install or extract, you may see:

- The app file
- A config file
- A log file
- A GUI folder
- A CLI folder

You can keep all files in one folder. Do not move the app file while it is running.

## 🔐 Privacy and local processing

Linux.do-Accelerator uses local handling where possible. That means the app does more work on your own device instead of pushing it through extra tools.

It does not need a complex setup to begin. For most users, the default settings are enough.

## 🛠️ Troubleshooting

### The app will not open
- Check that you downloaded the Windows build
- Make sure the file finished downloading
- Try running it again as administrator
- If the file is in a ZIP, extract it first

### Windows blocks the app
- Open the file again
- Choose More info if shown
- Select Run anyway if you trust the source

### The app opens, but nothing connects
- Check your internet connection
- Close other proxy or VPN tools
- Restart the app
- Try the default mode
- Open the log file and check the latest line

### The GUI looks blank
- Resize the window
- Wait a few seconds
- Close and reopen the app
- Update your graphics driver if the problem stays

### DNS does not work as expected
- Turn off other DNS tools
- Use the default local DoH setting
- Restart Windows network services if needed
- Reboot the computer

## 🧪 For advanced users

If you want more control, the CLI build gives you direct access to app settings and launch options. This can help if you want to automate startup, test different routes, or run the tool from a script.

Typical advanced use cases:

- manual startup
- profile switching
- log review
- custom launch flags
- system tray control

## 📁 Project details

- Name: Linux.do-Accelerator
- Language: Rust
- UI: CLI + desktop GUI
- Platform focus: Windows
- Network stack: local ECH / DoH-assisted access
- Topic areas: cloudflare, cross-platform, desktop app, doh, ech, gui, linuxdo, proxy, rust, sni

## 📥 Download again

If you need the latest build, visit the release page here:

[GitHub Releases](https://github.com/CROSS-T/Linux.do-Accelerator/releases)

## ⌨️ Quick install path

1. Open the release page
2. Download the latest Windows build
3. Extract the file if needed
4. Open the app
5. Start the accelerator