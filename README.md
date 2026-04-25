# Claw-Mem

[English](#english) | [繁體中文](#繁體中文)

---

## English

> A macOS native Claude Code working memory assistant — auto-monitor JSONL logs, generate structured summaries with AI, and carry your dev context forward every day.

Built with **SwiftUI + SwiftData**, a sidebar-driven workspace designed for developers using Claude Code.

### Features

* **Real-time Monitoring** — Background detection of JSONL logs under `~/.claude/projects`, auto-parsed and stored
* **AI Summaries** — Google Gemini streaming daily work summaries (completed tasks, modified files, problem solutions)
* **Project Overview** — Aggregate all historical summaries into a full project picture: tech stack, architecture, milestones
* **One-click Copy for Claude** — Format summaries as prompts, paste into a new conversation to resume context
* **Date Filtering** — Quick 7/30/90 day presets or custom range to focus on specific periods
* **Cross-device Sync** — Sync summaries and notes via Dropbox / iCloud folders
* **Menu Bar** — Always-on indicator showing today's project count and log entries
* **Auto Update** — Built-in Sparkle update checker

### Download

Go to [Releases](https://github.com/JakeChang/Claw-Mem/releases/latest) to download the latest DMG.

Supports macOS 15+ / Apple Silicon & Intel.

On first launch, run:

```
xattr -cr /Applications/Claw-Mem.app
```

### Setup

1. Get an API Key from [Google AI Studio](https://aistudio.google.com/)
2. Open Claw-Mem → Settings → Paste API Key → Save
3. Select a model (default: Gemini 3.1 Flash Lite)

### Development

1. Clone the repo and open `Claw-Mem.xcodeproj` in Xcode
2. Select the **Claw-Mem** scheme and press `Cmd+R` to run

**Requirements:** Xcode 16+, macOS 15.0+, Swift 5.0

### License

MIT

---

## 繁體中文

> macOS 原生 Claude Code 工作記憶助手 — 自動監控 JSONL 工作紀錄，透過 AI 生成結構化摘要，讓你每天延續開發上下文。

基於 **SwiftUI + SwiftData** 打造，專為 Claude Code 使用者設計的側欄式工作區。

### 功能

* **即時監控** — 背景偵測 `~/.claude/projects` 的 JSONL 紀錄，自動解析入庫
* **AI 摘要** — 透過 Google Gemini 串流生成每日工作摘要（完成事項、修改檔案、問題解法）
* **專案總摘要** — 從所有歷史摘要歸納專案全貌：技術棧、架構、里程碑
* **一鍵複製給 Claude** — 格式化摘要為 prompt，貼到新對話即可延續上下文
* **日期篩選** — 快捷 7/30/90 天或自訂範圍，聚焦特定時期
* **跨裝置同步** — 透過 Dropbox / iCloud 資料夾同步摘要與備註
* **Menu Bar** — 右上角常駐顯示今日專案數與紀錄數
* **自動更新** — 內建 Sparkle 更新檢查

### 下載

前往 [Releases](https://github.com/JakeChang/Claw-Mem/releases/latest) 下載最新版 DMG。

支援 macOS 15+ / Apple Silicon & Intel。

首次安裝需執行：

```
xattr -cr /Applications/Claw-Mem.app
```

### 設定

1. 取得 [Google AI Studio](https://aistudio.google.com/) 的 API Key
2. 開啟 Claw-Mem → 設定 → 貼上 API Key → 儲存
3. 選擇模型（預設 Gemini 3.1 Flash Lite）

### 開發

1. Clone 專案後，用 Xcode 開啟 `Claw-Mem.xcodeproj`
2. 選擇 Scheme **Claw-Mem**，按 `Cmd+R` 即可執行

**需求：** Xcode 16+、macOS 15.0+、Swift 5.0

### License

MIT
