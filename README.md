<p align="center">
  <img src="https://github.com/kimfull/GemList/raw/main/screenshots/en/Frame%201.png" alt="GemList Banner" width="720" />
</p>

<h1 align="center">💎 GemList: The Ultimate Sidebar for Gemini</h1>

<p align="center">
  <strong>Your Gemini, Organized. — 你的 Gemini，井然有序。</strong><br/>
  Sidebar navigation, chat pins & editing, and Gems manager.<br/>
  側邊導覽、對話釘選與編輯、以及 Gems 管理器。
</p>

<p align="center">
  <a href="#-english">🇬🇧 en English</a>&nbsp;&nbsp;|&nbsp;&nbsp;<a href="#-繁體中文">🇹🇼 繁體中文</a>&nbsp;&nbsp;|&nbsp;&nbsp;<a href="CHANGELOG.md">📝 Changelog</a>&nbsp;&nbsp;|&nbsp;&nbsp;<a href="privacy_policy.md">🔒 Privacy Policy</a>
</p>

---

## 🇬🇧 English

### 🚀 What is GemList?

Google Gemini is brilliant, but scrolling through endless chat history to find that *one perfect answer*? Not so much. Enter **GemList** — a bespoke Chrome Extension that injects a powerful and elegant sidebar directly into your Gemini interface. It's not just a table of contents; it's your personal AI conversation manager.

Stop scrolling endlessly. Start organizing like a pro.

### ✨ Feature Overview

#### 📑 Smart Outline — Instant Navigation
GemList automatically extracts every conversation turn (your question + Gemini's reply) and builds a clickable outline in the sidebar. Click any item to teleport directly to that message — even if the conversation is hundreds of rounds long.

- **Scroll-Spy**: As you scroll through the main chat, the sidebar automatically highlights the conversation you're currently reading.
- **Lazy Load Support**: For ultra-long conversations where Gemini unloads older messages from the DOM, GemList detects missing elements and auto-scrolls to trigger loading, then jumps to the target.

<p align="center">
  <img src="https://github.com/kimfull/GemList/raw/main/screenshots/en/Frame%201.png" alt="Smart Outline" width="640" />
</p>

#### 💎 Gems Manager — Sync, Sort, Quick Switch
Manage all your custom Gems from a dedicated tab in the sidebar. No more navigating to the Gems page just to switch.

- **One-Click Sync**: Fetch your latest Gems list from Google with a single button press. The extension navigates to the Gems page, extracts the data, and returns — all automatically.
- **Drag-and-Drop Sorting**: Arrange your Gems in any order you prefer. Your custom order syncs across devices via Chrome Sync Storage.
- **Quick Switch**: Click any Gem to immediately switch to it. The currently active Gem is highlighted.
- **Edit Shortcut**: Click the first few characters of any Gem's name to jump directly to its edit page.

<p align="center">
  <img src="https://github.com/kimfull/GemList/raw/main/screenshots/en/Frame%202.png" alt="Gems Manager" width="640" />
</p>

#### 📌 Pin & Save — Never Lose Important Context
Found a golden response? Pin it! Pinned conversations stick to the top of the sidebar in a dedicated pinned layer, acting as persistent knowledge bookmarks.

- **Pinned Layer**: Pinned items live in a collapsible section above the main outline.
- **Click-to-Jump**: Click a pinned item to scroll the main chat to the corresponding message.
- **Cross-Conversation**: Pins are saved per conversation and persist across page reloads.

<p align="center">
  <img src="https://github.com/kimfull/GemList/raw/main/screenshots/en/Frame%203.png" alt="Pin & Save" width="640" />
</p>

#### ✏️ Edit Titles & Markdown Export
Rename any conversation turn's title for clarity. GemList also extracts conversation content as clean, well-formatted Markdown.

- **Inline Editing**: Click the first few characters of any title to enter edit mode. Save with Enter, cancel with Esc.
- **Modified Indicator**: Edited titles display an "M" badge so you always know which titles are custom.
- **Restore Original**: One click to revert any edited title back to its original text.
- **One-Click Copy**: Copy a single round or the entire conversation. Output is perfectly formatted Markdown — headings, code blocks, tables, links, and lists all preserved.

<p align="center">
  <img src="https://github.com/kimfull/GemList/raw/main/screenshots/en/Frame%204.png" alt="Edit Titles & Export" width="640" />
</p>

#### 🔐 Your Data, Your Control
GemList is privacy-first by design. All data processing happens entirely on your device.

- **Zero External Requests**: No data is ever sent to any external server. Period.
- **Local Storage**: Conversation caches and pin data are stored in Chrome's local storage.
- **Export & Import**: Full backup and restore via JSON files. Download your data anytime with the export button, or restore from a backup with the import button.

<p align="center">
  <img src="https://github.com/kimfull/GemList/raw/main/screenshots/en/Frame%205.png" alt="Data Control" width="640" />
</p>

#### 🪶 Ultra-Lightweight & Thoughtfully Designed

- **Pure Vanilla JS**: No React, no Vue, no frameworks. Just clean, fast, dependency-free JavaScript.
- **Resizable Sidebar**: Drag the edge to adjust width (300–600px). The sidebar automatically adapts to window size.
- **Collapsible**: Minimize the sidebar to a tiny icon when you don't need it. Click to restore.
- **i18n**: Full support for English, Traditional Chinese (繁體中文), and Simplified Chinese (简体中文).
- **Smart DOM Extraction**: A robust, multi-layered scoring system identifies the correct conversation container even when Gemini updates its page structure.

### 🔗 Quick Links

| Resource | Link |
|---|---|
| 📝 Changelog | [CHANGELOG.md](CHANGELOG.md) |
| 🔒 Privacy Policy | [privacy_policy.md](privacy_policy.md) |
| 🐛 Issues & Feedback | [GitHub Issues](https://github.com/kimfull/GemList/issues) |

---

## 🇹🇼 繁體中文

### 🚀 GemList 是什麼？

Google Gemini 很聰明，但想在冗長的對話歷史中找到那個「完美回答」？往往得一直滾一直滾，滾到天荒地老。**GemList** 就是為此而生的 — 一個量身打造的 Chrome 擴充功能，為你的 Gemini 頁面無縫注入一個「強大且優雅的側邊欄」。它不僅是目錄，更是你的 AI 對話管理中心。

別再無止盡地滾頁面了。像個 Pro 一樣管理你的對話吧。

### ✨ 功能總覽

#### 📑 智慧大綱 — 瞬間導航
GemList 自動提取每一輪對話（你的提問 + Gemini 的回覆），在側邊欄建立可點擊的大綱。點一下就能瞬間跳到該訊息 — 即使對話已經長達幾百輪也不怕。

- **捲動追蹤 (Scroll-Spy)**：當你在主聊天區域捲動時，側邊欄會自動高亮目前正在閱讀的那一輪對話。
- **惰性載入支援 (Lazy Load)**：超長對話中，如果 Gemini 已經從 DOM 卸載了較早的訊息，GemList 會偵測到，並自動觸發捲動載入，最終定位到目標位置。

<p align="center">
  <img src="https://github.com/kimfull/GemList/raw/main/screenshots/tw/Frame%201%20tw.png" alt="智慧大綱" width="640" />
</p>

#### 💎 Gems 管理器 — 同步、排序、快速切換
在側邊欄的專屬分頁中管理你所有的自訂 Gems。再也不用跑到 Gems 頁面才能切換了。

- **一鍵同步**：按一下按鈕，擴充功能會自動跳轉到 Gems 頁面抓取最新清單，完成後帶著資料自動跳回來。全程無感。
- **拖曳排序**：按住拖曳手柄就能自由調整 Gems 的順序。你的自訂排序會透過 Chrome Sync Storage 跨裝置同步。
- **快速切換**：點擊任何 Gem 即可立即切換。目前使用中的 Gem 會有高亮標記。
- **編輯捷徑**：點擊 Gem 名稱的前幾個字，可以直接跳到該 Gem 的編輯頁面。

<p align="center">
  <img src="https://github.com/kimfull/GemList/raw/main/screenshots/tw/Frame%202%20tw.png" alt="Gems 管理器" width="640" />
</p>

#### 📌 釘選與收藏 — 絕不遺失重要上下文
看到超棒的回答？釘選起來！釘選的對話會固定顯示在側邊欄頂部的專屬區域，就像你的知識書籤一樣。

- **釘選層**：釘選的項目住在一個可收合/展開的專屬區塊中，位於主要大綱的上方。
- **點擊跳轉**：點擊釘選項目即可讓主聊天區域捲動到對應的訊息。
- **跨重載持久化**：釘選資料按對話 ID 儲存，且在頁面重新載入後仍然保留。

<p align="center">
  <img src="https://github.com/kimfull/GemList/raw/main/screenshots/tw/Frame%203%20tw.png" alt="釘選與收藏" width="640" />
</p>

#### ✏️ 編輯標題與 Markdown 匯出
將任何對話輪次的標題改名為更清晰的敘述。GemList 同時能將對話內容提取為乾淨、格式化的 Markdown。

- **行內編輯**：點擊標題的前幾個字即可進入編輯模式。按 Enter 儲存、按 Esc 取消。
- **已修改標記**：被編輯過的標題會顯示「M」徽章，讓你隨時知道哪些是自訂標題。
- **還原原始**：一鍵還原任何已編輯的標題為原始文字。
- **一鍵複製**：複製單一輪次或整段對話。輸出為完美格式的 Markdown — 標題、程式碼區塊、表格、連結、清單全部完整保留。

<p align="center">
  <img src="https://github.com/kimfull/GemList/raw/main/screenshots/tw/Frame%204%20tw.png" alt="編輯標題與匯出" width="640" />
</p>

#### 🔐 你的資料，你做主
GemList 從設計上就以隱私為優先。所有資料處理完全在你的裝置上進行。

- **零外部請求**：不會將任何資料傳送到任何外部伺服器。句號。
- **本地儲存**：對話快取與釘選資料儲存在 Chrome 的 Local Storage 中。
- **匯出與匯入**：透過 JSON 檔案完整備份與還原。隨時用匯出按鈕下載你的資料，或用匯入按鈕從備份還原。

<p align="center">
  <img src="https://github.com/kimfull/GemList/raw/main/screenshots/tw/Frame%205%20tw.png" alt="資料自主" width="640" />
</p>

#### 🪶 極致輕量與精心設計

- **純原生 JavaScript**：沒有 React、沒有 Vue、沒有任何框架。就是乾淨、快速、零依賴的 JavaScript。
- **可調整寬度**：拖曳邊緣調整側邊欄寬度（300–600px）。側邊欄會自動適應視窗大小。
- **可收合**：不需要時可以將側邊欄最小化成一個小圖示。點一下就能恢復。
- **多語系 (i18n)**：完整支援 English、繁體中文、简体中文。
- **智慧型 DOM 提取**：採用多層評分機制精準識別正確的對話容器，即使 Gemini 更新頁面結構也不怕。

### 🔗 相關連結

| 資源 | 連結 |
|---|---|
| 📝 更新紀錄 | [CHANGELOG.md](CHANGELOG.md) |
| 🔒 隱私權政策 | [privacy_policy.md](privacy_policy.md) |
| 🐛 問題回報與建議 | [GitHub Issues](https://github.com/kimfull/GemList/issues) |

---

<p align="center">
  Made with ❤️ by <strong>KimFull</strong>
</p>
