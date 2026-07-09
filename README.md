# TubeX

[![Swift](https://img.shields.io/badge/Swift-5.10+-orange.svg)](https://swift.org)
[![iOS](https://img.shields.io/badge/iOS-16.0+-blue.svg)](https://developer.apple.com/ios/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## 🌐 Introduction / 專案簡介 / 项目简介 / はじめに

* **English:** A lightweight iOS Proof of Concept (PoC) app built with SwiftUI and AVFoundation, demonstrating how to parse and play YouTube audio streams seamlessly in the background with native looping.
* **繁體中文:** 一款基於 SwiftUI 與 AVFoundation 的 iOS 概念驗證（PoC）微型 App，展示如何動態解析並在背景流暢播放 YouTube 音訊串流，並實現原生無縫循環。
* **简体中文:** 一款基于 SwiftUI 与 AVFoundation 的 iOS 概念验证（PoC）微型 App，展示如何动态解析并在后台流畅播放 YouTube 音频串流，并实现原生无缝循环。
* **日本語:** SwiftUI と AVFoundation で構築された軽量な iOS 概念実証（PoC）アプリです。YouTube のオーディオストリームを解析し、ネイティブのループ機能を用いてバックグラウンドでシームレスに再生する技術を実証します。

---

## ⚠️ DISCLAIMER / 免責聲明 / 免責事項

* **English:** This project is for **educational and research purposes only**. It serves as a technical demonstration of iOS `AVFoundation` capability. This app is **NOT** compliant with YouTube's Terms of Service (ToS) and **WILL NOT** be published to the App Store. Use at your own risk.
* **繁體中文：** 本專案僅供**學術研究與個人學習**使用，主要展示 iOS `AVFoundation` 音訊背景處理技術。本專案違反 YouTube 服務條款，**絕不上架 App Store**。使用者須自行承擔相關風險。
* **简体中文：** 本项目仅供**学术研究与个人学习**使用，主要展示 iOS `AVFoundation` 音视频后台处理技术。本项目违反 YouTube 服务条款，**绝不上架 App Store**。用户须自行承担相关风险。
* **日本語：** 本プロジェクトは**教育および研究目的のみ**の概念実証（PoC）です。iOS `AVFoundation` によるバックグラウンド再生の技術デモであり、YouTube の利用規約に違反するため **App Store への公開は行いません**。ご利用は自己責任でお願いします。

---

## 🚀 Features / 專案特點 / 项目特点 / 主な機能

### English
* **Background Playback:** Keeps playing when the device is locked or minimized (Requires Background Modes).
* **Gapless Looping:** Uses native `AVPlayerLooper` for 100% flawless single-track looping.
* **Stream Parsing:** Dynamically fetches metadata and highest-quality audio streams.
* **Anti-Blocking:** Implements User-Agent spoofing to prevent stream throttling.

### 繁體中文
* **背景播放：** 支援鎖屏或 App 縮小後持續播放音訊（需開啟 Xcode Background Modes）。
* **完美循環：** 採用原生 `AVPlayerLooper` 達到 100% 無縫單曲循環。
* **串流解析：** 動態解析 YouTube 影片資訊並抓取最高畫質的純音訊流。
* **防禦阻擋：** 內建 User-Agent 偽裝機制，防止串流被官方阻擋。

### 简体中文
* **后台播放：** 支持锁屏或 App 缩小后持续播放音频（需开启 Xcode Background Modes）。
* **完美循环：** 采用原生 `AVPlayerLooper` 实现 100% 无缝单曲循环。
* **串流解析：** 动态解析 YouTube 视频信息并抓取最高画质的纯音频流。
* **防御阻挡：** 内置 User-Agent 伪装机制，防止串流被官方阻挡。

### 日本語
* **バックグラウンド再生：** 画面ロック時やアプリ非アクティブ時でも再生を維持（Background Modes が必要）。
* **シームレスループ：** ネイティブの `AVPlayerLooper` を使用し、100% 途切れのない単曲ループを実現。
* **ストリーム解析：** YouTube のメタデータおよび最高画質のオーディオストリームを動的に取得。
* **ブロック回避：** ストリーミングの遮断を防ぐため、カスタム User-Agent 偽装を実装。

---

## 📦 Credits & Dependencies / 致謝與依賴 / 致谢与依赖 / 謝辞と依存関係

* **English:** This project heavily relies on the following open-source library to extract video metadata and stream URLs:
* **繁體中文：** 本專案高度依賴以下開源項目，用於解析影片中繼資料與動態選取串流網址：
* **简体中文：** 本项目高度依赖以下开源项目，用于解析视频元数据与动态选取串流网址：
* **日本語：** 本プロジェクトは、動画のメタデータおよびストリーム URL を抽出するために、以下のオープンソースライブラリに深く依存しています：

👉 **[YouTubeKit](https://github.com/alexeichhorn/YouTubeKit)** (MIT License)

---

## 📄 License / 授權條款 / 授权条款 / ライセンス

* **English:** This project is open-sourced under the [MIT License](LICENSE).
* **繁體中文：** 本專案採用 [MIT 授權條款](LICENSE) 開源。
* **简体中文：** 本项目采用 [MIT 授权条款](LICENSE) 开源。
* **日本語：** 本プロジェクトは [MIT ライセンス](LICENSE) のもとでオープンソースとして公開されています。
