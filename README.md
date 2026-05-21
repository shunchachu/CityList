# 📍 城事清單 CityList

> **「標記角落，點亮城市」—— 結合公民科技與社群力量的城市共創地圖。**

[![Web MVP Demo](https://img.shields.io/badge/Demo-Live_Preview-success?style=for-the-badge&logo=github)](#)
[![Tech Stack](https://img.shields.io/badge/Frontend-Tailwind_CSS_|_HTML/JS-blue?style=for-the-badge)](#)
[![Design](https://img.shields.io/badge/UI/UX-Mobile_First-purple?style=for-the-badge)](#)

## 📖 專案概述 (Project Overview)

「城事清單 CityList」是一款由下而上推動城市進化的共創 App。傳統的市政信箱往往是單向且封閉的，本專案致力於將「城市治理」與「地方創生」遊戲化、社群化。

透過雙軌視角與動態的標記系統，市民可以輕鬆在地圖上揪出交通痛點、發掘觀光秘境，並與社群共同見證城市改變的軌跡。本專案高度契合 **SDG 11（建構具包容、安全、韌性及永續特質的城市與鄉村）** 的發展願景。

## ✨ 核心特色 (Core Features)

### 1. 🚦 雙軌視角切換 (Dual-Mode Interface)
首頁提供全局一鍵切換，針對不同領域的城市議題進行精準收集：
* **🚦 交通模式**：專注於解決負面痛點（如：視線死角、行人空間受壓迫、標線不清）。
* **🏞️ 觀光模式**：專注於發掘潛力與文化創生（如：潛力秘境、閒置空間活化、歷史記憶）。

### 2. 🔴🟢🔵 三色燈號演化系統 (The 3-Color Pin System)
捨棄單純的「抱怨」，導入具備時間軸與成就感的標記演化邏輯：
* **🔴 差 (Bad)**：標記急需解決的痛點或待開發的廢墟。
* **🟢 良 (Good)**：表揚值得學習的優良設計或模範景點。
* **🔵 已改善 (Improved) [🔥 核心殺手鐧]**：當紅點被解決後，通報者可將其升級為藍點。**系統將強制要求上傳「改善前 (Before)」與「改善後 (After)」的對比照片**，用最強烈的視覺對比證明進步真實發生。

### 3. 💬 深度社群互動 (Community Engagement)
每個地圖標記都擁有獨立的詳細介面，市民不僅能查看圖文，還能進行以下互動：
* **👍 附議 (+1)**：聚集眾人力量，讓最嚴重的問題浮上檯面。
* **💡 建議與留言**：不只是點出問題，更能在留言區共同激盪出優化解方。

## 💻 技術架構 (Tech Stack & Architecture)

目前展示版本為 **Web-based MVP (最小可行性產品)**，專注於完整呈現 UI/UX 流程與核心業務邏輯，以便於瀏覽器環境下直接跨平台展示。

* **前端展示**：HTML5, 原生 JavaScript (Vanilla JS)
* **樣式排版**：Tailwind CSS (v3) - 實作高質感的 Mobile-First 響應式介面
* **圖示系統**：FontAwesome 6 (取代圖片依賴，確保穩定渲染)
* **未來整合藍圖 (Roadmap)**：
  * **Framework**: 預計採用 React Native 進行原生 App 封裝。
  * **Backend & DB**: 採用 Supabase (PostgreSQL) 處理使用者驗證與空間地理數據 (PostGIS)。
  * **Map Engine**: 串接 OpenStreetMap 實現免 API Key 的開源地圖載入。
