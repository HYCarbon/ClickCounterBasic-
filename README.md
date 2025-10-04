# ClickCounter

[![Kotlin](https://img.shields.io/badge/Kotlin-2.0+-blue?logo=kotlin)](https://kotlinlang.org)
[![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-2.0+-pink?logo=android)](https://developer.android.com/jetpack/compose)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## 🌟 專案簡介

ClickCounter 是一個簡潔而功能完備的計數器應用，靈感來自於敲木魚手錶遊戲。它將簡單的點擊動作轉化為帶有儀式感的計數體驗。作為 Jetpack Compose 初學者的實踐專案，它展示了現代 Android 開發的最佳實務。

---

## ✨ 主要功能

* **點擊計數** - 輕觸按鈕增加計數，簡單直覺
* **資料持久化** - 使用 DataStore 技術，確保計數在應用程式重新啟動後依然保留
* **現代化 UI** - 採用 Jetpack Compose 建構，介面簡潔美觀
* **回應式設計** - 適應不同螢幕尺寸的裝置

---

## 🚀 快速開始

### 環境需求
* Android Studio
* Android SDK API 級別 24 或更高
* Kotlin 2.0+
* Gradle 8.8+

### 安裝步驟

1. 複製專案：
   ```bash
   git clone https://github.com/NWMA-FYWF/ClickCounter.git
   ```

2. 在 Android Studio 中開啟專案：
   - 啟動 Android Studio
   - 選擇 "Open an existing project"
   - 導覽至專案資料夾並選擇

3. 同步 Gradle 相依性：
   - 點選 "Sync Now" 或在 Terminal 中執行 `./gradlew build`

4. 執行應用程式：
   - 連接 Android 裝置或啟動模擬器
   - 點選 "Run" 按鈕或按下 Shift+F10

---

## 📱 使用說明

1. 啟動應用程式後，您會看到目前計數顯示在螢幕上
2. 點選 "Click here" 按鈕以增加計數
3. 計數會自動儲存，即使關閉應用程式後重新啟動也不會遺失
4. 資料透過 Android 的 DataStore 技術進行持久化儲存

---

## 🔧 技術堆疊

* **Kotlin** - 現代 Android 開發語言
* **Jetpack Compose** - 現代 UI 框架
* **DataStore** - 資料持久化儲存解決方案
* **Material Design 3** - 設計語言與元件庫

---

## 📄 License

MIT License - 可自由使用、修改、散佈（但請保留原作者資訊）🙏