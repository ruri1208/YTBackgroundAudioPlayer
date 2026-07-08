# YTBackgroundAudioPlayer

[![Swift](https://img.shields.io/badge/Swift-5.10+-orange.svg)](https://swift.org)
[![iOS](https://img.shields.io/badge/iOS-16.0+-blue.svg)](https://developer.apple.com/ios/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

A lightweight, minimal iOS Proof of Concept (PoC) app built with SwiftUI and AVFoundation, demonstrating how to parse and play YouTube audio streams seamlessly in the background with native looping capabilities.

> **⚠️ DISCLAIMER / 免責聲明**
> 
> **English:** This project is for **educational, research, and personal use only**. It serves as a technical demonstration of iOS `AVFoundation` capability and container cache tracking. This app is **NOT** compliant with YouTube's Terms of Service (ToS) and **WILL NOT** be published to the App Store. Use at your own risk.
> 
> **中文：** 本專案僅供**學術研究、個人學習與技術分享**使用。主要展示 iOS `AVFoundation` 音訊串流背景處理與快取追蹤技術。本專案違反 YouTube 服務條款（禁止背景播放與提取音訊），**絕不上架 App Store**。請勿用於任何商業用途，使用者須自行承擔相關風險。

---

## Features / 專案特點

* **Background Audio Playback:** Keeps playing even when your iPhone is locked or the app is minimized (Requires Background Modes enabled).
* **Flawless Looping:** Implements Apple's native `AVPlayerLooper` with `AVQueuePlayer` for 100% gapless single-track looping.
* **Stream Parsing:** Fetches metadata and highest-quality audio-only streams dynamically.
* **Cache Monitor:** Includes a built-in sandbox cache tracker and manual cleaner.
* **Anti-Blocking Guard:** Uses custom user-agent spoofing to prevent stream throttling.

## Technical Stack / 技術棧

* **UI Framework:** SwiftUI
* **Audio Engine:** AVFoundation (`AVQueuePlayer`, `AVPlayerLooper`, `AVURLAsset`)
* **Concurrency:** Swift Async/Await (`Task`, `@MainActor`)

---

## Requirements / 運行環境

* iOS 16.0+
* Xcode 15.0+
* Swift 5.10+

---

## Setup Instructions / 如何在本地運行

To run this project on your personal iOS device, you must configure the background capabilities manually in Xcode:

1. Clone this repository to your local machine.
2. Open the project in Xcode.
3. Select your project target, go to **Signing & Capabilities**.
4. Click **+ Capability** and add **Background Modes**.
5. Check the box for **Audio, AirPlay, and Picture in Picture**.
6. Connect your iPhone, select your development team, and press **Run (Cmd + R)**.

---

## Credits & Dependencies / 致謝與依賴項目

This project heavily relies on the following amazing open-source library:

* **[YouTubeKit](https://github.com/alexeichhorn/YouTubeKit)** (MIT License) - Used for extracting video metadata and locating media stream URLs.

Special thanks to the open-source community for making media parsing accessible for educational research.

---

## License / 授權條款

This project is open-sourced under the [MIT License](LICENSE). 
