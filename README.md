# 🧳 離職集點卡 Resign Stamp Card

> 一個幫你記錄「我不幹了」與「快樂小事」的心理陪伴小工具 ✨  
> 跨裝置同步、可愛怪獸風格、實用又紓壓的集點系統！
> 0804 上午 1:27 依據大家的回饋更新了快樂集點卡顯示內容
> 同步將所有"離職"改成"逃出"
---

## 🧪 開發測試中

本專案目前仍在開發與測試階段，尚未完成所有功能與優化，請勿直接用於正式環境。  
部分資料與視覺內容為個人原創，**未經授權請勿使用、複製或散佈**。

---

## 🐾 專案介紹

每天都想離職嗎？那就來「蓋章」吧。  
這個 App 讓你記錄：
- 每一次「我不想幹了」的瞬間
- 每一個微小但真實的快樂時刻

用【離職集點卡】與【快樂集點卡】對抗職場焦慮，陪你一起撐過去 🐌

---

## ✨ 功能特色

- ✅ 支援 Google 登入，資料自動雲端同步
- 🔖 逃出集點卡（記錄不爽瞬間，最多 50 格）
- 🌈 快樂集點卡（每集滿 10 格自動減少 1 格離職章）
- 📊 進度條提示：你還能撐幾次？
- 🧸 可愛風格蓋章怪獸，讓壓力瞬間軟化
- ⚙️ 可自訂格數、檢視歷史記錄

---

## 🚀 線上試用

🔗 GitHub Pages：[https://anjui2025.github.io/resign-stamp-card](https://anjui2025.github.io/resign-stamp-card)

> 若畫面空白或無法載入，請確認已使用支援 Firebase 的網頁環境。

---

## 🔧 技術架構

- Flutter 3.x（Web Build）
- Firebase Auth（Google 登入）
- Firebase Firestore（雲端儲存）
- FirebaseUI（登入介面）
- 響應式設計支援手機與桌機
- 自訂 UI 元件（HoverButton 等）

---

## 📁 專案結構

```bash
/lib
 ┣ main.dart              # 入口點
 ┣ pages/                 # 各主頁面（首頁、離職卡、快樂卡、設定等）
 ┣ widgets/               # 自訂元件（印章格、對話框等）
 ┗ models/                # 資料結構（StampData、AppState）

---

📜 授權聲明
本專案採用 MIT License（但部分內容例外）：

原始程式碼：可自由使用與改作，請保留授權與貢獻者資訊。

圖像素材與插圖（怪獸、Logo 等）：僅供學習用途，未經授權請勿使用於任何商業或公開用途。

若你有合作或使用需求，請先聯繫作者。

---

🧑‍💻 作者資訊
由 anjui 開發
caramel.unit@gmail.com

---
# 🧳 Resign Stamp Card

> A simple mental support tool that helps you track every "I wanna quit" moment and every tiny joy ✨  
> Cross-device sync, cute monster vibes, and a surprisingly therapeutic point-collection system!

---

## 🧪 Currently in Development

This project is still under active development and testing.  
Not all features are complete or optimized, so please avoid using it in production environments.  
Some assets and visuals are original creations—**do not use, copy, or redistribute without permission.**

---

## 🐾 Project Overview

Thinking about quitting every day? Then stamp it.  
This app helps you log:
- Every moment you feel like yelling “I quit!”
- Every small but genuine joy

With both a *Resignation Stamp Card* and a *Happiness Stamp Card*, this tool helps you cope with workplace anxiety—one stamp at a time 🐌

---

## ✨ Key Features

- ✅ Google Sign-in with automatic cloud sync
- 🔖 Resignation Card (up to 50 stamps for those “I’m done” moments)
- 🌈 Happiness Card (collect 10 joyful stamps to erase 1 resignation stamp)
- 📊 Progress indicators: how close are you to the edge?
- 🧸 Cute monsters to help soften the daily stress
- ⚙️ Customizable card size and history tracking

---

## 🚀 Try It Online

🔗 GitHub Pages: [https://anjui2025.github.io/resign-stamp-card](https://anjui2025.github.io/resign-stamp-card)

> If you see a blank screen or loading issues, make sure you're using a browser that supports Firebase web apps.

---

## 🔧 Tech Stack

- Flutter 3.x (Web Build)
- Firebase Auth (Google Sign-In)
- Firebase Firestore (Cloud Storage)
- FirebaseUI (Authentication UI)
- Responsive design for mobile and desktop
- Custom UI widgets (e.g., HoverButton)

---

## 📁 Project Structure

```bash
/lib
 ┣ main.dart              # Entry point
 ┣ pages/                 # All pages (home, resignation card, happiness card, settings, etc.)
 ┣ widgets/               # Reusable components (stamp grid, dialogs, etc.)
 ┗ models/                # Data models (StampData, AppState)

---

📜 License
This project uses the MIT License, with some exceptions:

Source Code: Free to use and modify. Please retain credit and license info.

Visual Assets (e.g., monsters, logos): For learning/demo purposes only.
Do not use in commercial or public projects without permission.

For collaboration or licensing inquiries, please contact the author.

---

🧑‍💻 Author
Developed by anjui
📧 caramel.unit@gmail.com

---
