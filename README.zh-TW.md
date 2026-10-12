# PilotCut Windows 版

<p align="center">
  <a href="https://pilotcut.com">
    <img src="https://pilotcut.com/logo.png" alt="PilotCut Logo" width="80" height="80" />
  </a>
</p>

<p align="center">
  <b>真正幫你剪輯的影片編輯器 — 專為 Windows 打造的本機優先 AI Agent 影片剪輯工具</b>
</p>

<p align="center">
  <b>繁體中文</b> | <a href="README.md">English</a>
</p>

<p align="center">
  <a href="https://github.com/pilotcut/pilotcut-windows-releases/releases/latest"><img src="https://img.shields.io/github/v/release/pilotcut/pilotcut-windows-releases?style=flat-square&color=blue" alt="最新版本"></a>
  <a href="https://github.com/pilotcut/pilotcut-windows-releases/releases"><img src="https://img.shields.io/github/downloads/pilotcut/pilotcut-windows-releases/total?style=flat-square&color=green" alt="總下載量"></a>
  <a href="https://pilotcut.com"><img src="https://img.shields.io/badge/官方網站-pilotcut.com-orange?style=flat-square" alt="官方網站"></a>
</p>

---

## 專案介紹

**PilotCut** 是一款原生、本機優先、專為 AI Agent 設計的智慧影片剪輯軟體。只需透過 Claude Code、OpenAI Codex、Gemini CLI 或自訂 Agent 描述你想要的影片效果，PilotCut 便會將指令精準轉譯為具體的時間軸操作——自動粗剪、消除冗長空白、剔除贅字，並智慧插入 B-roll 輔助素材，且全程素材絕不離開你的本機電腦。

本儲存庫為 PilotCut Windows 版本的官方釋出管道，提供安裝程式下載、版本更新紀錄（Changelog）及相關發行資源。

---

## 核心特色

- **Agent 協同剪輯（Agent-in-the-Loop）**：透過 MCP（40+ 專屬工具）或 CLI 介面無縫連結 Claude Code、Codex、Gemini CLI 等 AI 工具。AI 提議剪輯方案，你掌握最終審核與微調權。
- **AI 自動去除贅字**：一鍵快速辨識並剪除口語中的「嗯」、「啊」、重複字詞與開頭失誤。
- **智慧靜音壓縮（Silence Collapse）**：自動緊縮冗長無聲停頓，同時保留自然流暢的說話節奏。
- **智慧 B-Roll 素材對位**：自動分析語音內容，將螢幕錄影、產品展示及輔助畫面精準對齊旁白節奏點。
- **100% 本機優先與隱私安全**：原始素材、代理檔（Proxy）與最終輸出均留在你的本機，無須上傳雲端，無用量點數限制。
- **原生時間軸與具名操作紀錄**：高效能原生播放與剪輯，每次 AI 修改皆為具名且可隨時復原（Undo）的獨立操作。
- **Windows 原生硬體加速優化**：多執行緒渲染架構，深度整合 Windows GPU 硬體編碼加速（DirectX 12 / NVENC / QuickSync / AMF）。

---

## 下載與安裝

### 方式一：直接下載安裝檔（推薦）

1. 前往 [**最新版本釋出頁面 (Latest Releases)**](https://github.com/pilotcut/pilotcut-windows-releases/releases/latest)。
2. 下載安裝程式：
   - **`PilotCut-Setup-x64.exe`**（標準 Windows 64 位元安裝檔）
   - *(可選)* 免安裝可攜版 zip 壓縮檔（若有提供）。
3. 執行安裝程式並依照指示完成安裝。
4. 從開始功能表或桌面捷徑啟動 PilotCut。

### 方式二：命令列 / 套件管理器安裝 *(即將推出)*

```powershell
# 透過 Winget 安裝 (即將推出)
winget install PilotCut.PilotCut
```

---

## 系統需求

| 項目 | 最低需求 | 建議規格 |
| :--- | :--- | :--- |
| **作業系統** | Windows 10 64 位元 (版本 19041 或以上) | Windows 11 64 位元 (最新版本) |
| **處理器 (CPU)** | Intel Core i5 (第 8 代以上) 或 AMD Ryzen 5 | Intel Core i7 / i9 (第 11 代以上) 或 AMD Ryzen 7 / 9 |
| **記憶體 (RAM)** | 8 GB RAM | 16 GB 以上 RAM |
| **顯示卡 (GPU)** | Intel UHD Graphics 630 / 獨立顯示卡 | NVIDIA GeForce GTX 1660 / RTX 系列或 AMD Radeon RX 5000+ |
| **硬碟空間** | 1 GB 可用空間（程式安裝） | SSD 固態硬碟，10 GB 以上可用空間（快取與專案輸出） |

---

## 軟體更新

PilotCut 內建自動更新檢查機制。當有新版本發布時：
- 軟體內將主動跳出更新通知，點擊即可一鍵升級。
- 您也可以隨時至 [Releases 頁面](https://github.com/pilotcut/pilotcut-windows-releases/releases) 手動下載最新安裝檔覆蓋更新。

---

## 社群與支援

本儲存庫僅提供安裝程式與版本釋出，並非產品問題追蹤區。

- **官方網站**：[https://pilotcut.com](https://pilotcut.com)
- **支援與回饋**：[support@pilotcut.com](mailto:support@pilotcut.com)
- **Twitter / X**：[@PilotCutCom](https://x.com/PilotCutCom)

---

## 授權條款

PilotCut for Windows 為專利商業軟體。詳細授權條款請參閱安裝程式中附帶之使用者授權合約 (EULA)。

---

<p align="center">Made by the <a href="https://pilotcut.com">PilotCut Team</a></p>
