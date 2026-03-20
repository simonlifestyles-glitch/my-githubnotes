# 📓 GitHub 使用筆記

## 什麼是 GitHub？
- GitHub 是一個程式碼與文件的雲端托管平台
- 建立在 Git（版本控制系統）之上
- 可以記錄每一次修改的歷史，隨時回溯

## 核心概念

### Repository（repo）
- 一個「專案資料夾」
- 可以放程式碼、筆記、文件、資料集等
- 分為 Public（公開）和 Private（私人）

### Markdown（.md）
- 一種輕量排版語法，純文字就能有格式
- GitHub 會自動把 .md 檔案渲染成排版頁面
- 常用語法：
  - `# 大標題`、`## 小標題`
  - `- 清單項目`
  - `**粗體**`、`*斜體*`

### Commit
- 每次儲存變更的動作叫做 commit
- 會記錄「誰、什麼時候、改了什麼」
- 相當於一個存檔點

### GitHub Pages
- 可以把 repo 裡的檔案變成免費網站
- 網址格式：`https://使用者名稱.github.io/repo名稱`
- 開啟方式：Settings → Pages → 選 main branch

## 常見用途（不需要寫程式）
- 📝 寫學習筆記（用 Markdown）
- 🌐 架靜態個人網站（GitHub Pages）
- 📂 備份與管理文件
- 🔍 瀏覽別人的開源專案與資源

## 操作流程：建立筆記網站

1. 註冊 GitHub 帳號
2. 建立新 Repository（勾選 Add README）
3. 編輯 README.md，用 Markdown 寫筆記
4. Commit changes 儲存
5. Settings → Pages → 開啟，取得網站網址

## 備註
- 免費帳號就夠一般使用
- 網頁上就能操作，不需安裝軟體
- Public repo 的內容任何人都可以看到


## Branches 與 Main

- **main** 是正式版本，永遠保持穩定可用
- **branch** 是平行的實驗空間，可以大膽修改而不影響 main
- 改好滿意後再「合併（merge）」回 main

類比：main = 書的出版版，branch = 編輯在另一份草稿上改稿

### 使用場景
- 想新增功能但怕改壞 → 開新 branch 實驗
- 多人協作，每人在自己的 branch 工作 → 完成後合併

---

## ＋ 選單功能說明

| 功能 | 用途 | 適合誰 |
|------|------|--------|
| New repository | 建新資料夾（最常用） | 所有人 |
| Import repository | 把別處專案搬進 GitHub | 開發者 |
| New codespace | 雲端版 VS Code 編輯器 | 開發者 |
| New issue | 開待辦票，記錄問題或任務 | 所有人 |
| New gist | 快速分享一段文字或程式碼 | 所有人 |
| New project | 看板式任務管理（像 Trello） | 進階用 |
| New organization | 建立團隊帳號，多人共管 repo | 團隊用 |

### 一般人最常用
- **New repository** — 建新筆記/專案資料夾
- **New issue** — 給自己記待辦，或回報軟體問題
- **New gist** — 快速分享一段文字
- **New project** — 管理多個任務（進階）
