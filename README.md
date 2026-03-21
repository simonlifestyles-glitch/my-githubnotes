# 📓 GitHub 使用筆記

> 給程式小白的 GitHub 入門筆記，從零開始也看得懂。

🔰 [GitHub 是什麼？（視覺化入門）](https://simonlifestyles-glitch.github.io/my-githubnotes/intro.html)

📊 [圖解筆記（Branch 與功能說明）](https://simonlifestyles-glitch.github.io/my-githubnotes/charts.html)

🗂️ [Repo 導覽列說明（視覺化）](https://simonlifestyles-glitch.github.io/my-githubnotes/navbar.html)

---

## 一、GitHub 是什麼？

可以把 GitHub 想成一個**雲端的資料夾＋時光機**：

- 📁 **雲端資料夾** — 把你的筆記、文件、程式碼存在網路上，任何裝置都能存取
- ⏪ **時光機** — 每次修改都會被記錄，隨時可以回到過去任何一個版本
- 🌐 **免費網站** — 可以把內容直接變成一個公開網站（GitHub Pages）
- 👥 **協作空間** — 多人可以同時在同一個專案上工作

**不寫程式也可以用來：** 寫學習筆記、架個人網站、備份文件、管理待辦事項。

---

## 二、幾個你需要知道的詞

### 📁 Repository（repo）— 專案資料夾
就是一個資料夾，所有東西都放在裡面。
- **Public** = 任何人都可以看到
- **Private** = 只有你自己看得到

### 💾 Commit — 存檔
每次修改完按下儲存的動作。每個 commit 都會記錄「誰、在什麼時候、改了什麼」，就像 Google 文件的版本紀錄。

### 🌿 Main 與 Branch — 正式版 vs 草稿版
- **main** = 正式出版的版本，永遠保持穩定
- **branch** = 另開一份草稿來實驗，改壞了也不影響 main，滿意了再合併回去

### 📝 Markdown（.md）— 簡易排版語法
寫筆記用的格式，純文字就能做出標題、清單、粗體等效果：
```
# 大標題
## 小標題
- 清單項目
**粗體文字**
```

### 🌐 GitHub Pages — 免費網站
把 repo 裡的檔案直接變成網站，免費、不需要租伺服器。
網址格式：`https://你的帳號.github.io/repo名稱`
不只是靜態文字頁面，只要是「純前端」的東西都能跑：

- HTML + CSS — 一般網頁、筆記
- JavaScript — 互動效果、動畫
- Canvas 遊戲 — 例如打磚塊（🎮[試玩看看](https://simonlifestyles-glitch.github.io/my-githubnotes/Breakout-game.html)）
- 資料視覺化 — D3.js 圖表（📊 [D3.js 資料視覺化範例](https://simonlifestyles-glitch.github.io/my-githubnotes/d3-demo.html)）

> 規則只有一個：不能有後端（不能連資料庫、不能跑 Python）。
> 瀏覽器能執行的，GitHub Pages 就能跑。
---

## 三、我能用 GitHub 做什麼？

### 🔰 入門：建立筆記網站
1. 建立新 Repository（勾選 Add a README file）
2. 點 README.md 右上角鉛筆，用 Markdown 寫筆記
3. 按 Commit changes 儲存
4. Settings → Pages → 選 main branch → Save
5. 等 1～2 分鐘，網站上線 ✅

### 🌿 進階：用 Branch 安全修改
1. 在 repo 頁面點 branch 選單，輸入新名稱建立 branch
2. 在新 branch 上自由修改，完全不影響 main
3. 確認沒問題後，合併（merge）回 main

### ➕ 右上角「＋」選單功能

| 功能 | 白話說明 | 誰會用到 |
|------|----------|----------|
| **New repository** | 建新資料夾 | ⭐ 所有人 |
| **New issue** | 開一張待辦票 | ⭐ 所有人 |
| **New gist** | 快速貼一段文字分享 | ⭐ 所有人 |
| **New project** | 建看板管理任務（像 Trello） | 進階用 |
| Import repository | 把別處專案搬進來 | 開發者 |
| New codespace | 雲端版編輯器 | 開發者 |
| New organization | 建立團隊帳號 | 團隊用 |

---

## 四、注意事項

- ✅ 免費帳號就夠一般使用
- ✅ 網頁上操作即可，不需安裝任何軟體
- ⚠️ Public repo 任何人都能看到，**不要放個資或密碼**
- ⚠️ 刪掉的內容在 commit 歷史裡還是找得到，敏感資訊從一開始就不要放

---

## 五、Repo 頁面功能說明

### 🛠️上方導覽列九個功能

| 功能 | 用途 | 適合誰 |
|------|------|--------|
| **Code** | 瀏覽所有檔案、編輯內容、查看 commit 歷史 | 所有人 |
| **Issues** | 開待辦票、回報問題、追蹤任務進度 | 所有人 |
| **Pull requests** | 提交修改申請，讓別人審核後再合併進 main | 協作用 |
| **Actions** | 查看自動化流程的執行紀錄與狀態 | 所有人 |
| **Projects** | 看板式任務管理，像 Trello 或 Notion 表格 | 進階用 |
| **Wiki** | 撰寫專案的說明文件，像內部百科全書 | 團隊用 |
| **Security** | 檢查安全漏洞、設定敏感資訊保護 | 開發者 |
| **Insights** | 查看 repo 的活動統計、貢獻者、流量數據 | 進階用 |
| **Settings** | 管理 repo 設定，包含 Pages、權限、刪除等 | 管理者 |

### 🔦一般人最常用
- **Code** — 每次進來都會用到
- **Issues** — 記待辦、追蹤問題
- **Actions** — 確認自動部署有沒有成功
- **Settings** — 開啟 GitHub Pages

- ---

## 六、如何在 GitHub 找到開源工具

### 1️⃣方法一：直接搜尋（最快）
右上角搜尋框輸入關鍵字，例如 `automation tool`、`note taking`、`data visualization`

搜尋後點 **Repositories**，用篩選器排序：
- **Most stars** — 最多人認可
- **Most forks** — 最多人拿去用
- **Recently updated** — 還有在維護

### 2️⃣方法二：用 Topics 標籤（最精準）
每個 repo 都有標籤，直接搜尋標籤：
- `topic:automation`
- `topic:self-hosted`
- `topic:productivity`

或直接開網址：`https://github.com/topics/automation`

### 3️⃣方法三：Awesome 清單（最省力）
GitHub 上有專門整理資源的清單，格式是 `awesome-[主題]`：
- `awesome-selfhosted` — 可以自架的工具大全
- `awesome-python` — Python 工具精選
- `awesome-n8n` — n8n 相關資源
- `awesome-mac` — Mac 工具推薦

搜尋 `awesome` 加上想找的領域，第一個結果通常就是最完整的清單。

### 4️⃣方法四：Trending（看最近流行什麼）
網址：`https://github.com/trending`

可以篩選語言、時間範圍（Today / This week / This month），是發現新工具的最佳管道。
Code教學`https://github.com/trending`

---

### 🤔找到後怎麼判斷值不值得用？

| 指標 | 說明 |
|------|------|
| ⭐ Stars | 越多代表越多人認可，1000+ 算不錯 |
| 🍴 Forks | 很多人拿去改，代表實用性高 |
| 最後更新時間 | 超過一年沒更新要注意，可能沒在維護 |
| Issues 活躍度 | 有人回報、有人修，代表專案還活著 |
| README 品質 | 說明清楚、有截圖的通常比較可靠 |

> 💡 對一般人最實用的組合：**Awesome 清單 + Trending**，不用想關鍵字，直接瀏覽就能找到好工具。


---

## 七、README.md 的意義

README.md 是一個 repo 的**封面說明頁**，當任何人進入 repo，GitHub 會自動把它的內容顯示在頁面下方，不需要點開就能看到。

類比：
- 一本書的**封底介紹**
- 一家店的**門口招牌**
- 一個資料夾的**目錄頁**

### ❓README 適合放什麼？
- 這個 repo 是做什麼的
- 裡面有哪些內容（目錄）
- 重要連結（視覺化頁面、相關資源）
- 使用說明或注意事項

### 📂每個資料夾都可以有自己的 README
不只是 repo 根目錄，子資料夾裡也可以放 README.md，進去那個資料夾時就會自動顯示。

---

### ❓為何需要資料夾結構

隨著筆記越來越多，如果全部放在同一層會變得混亂。資料夾結構讓每種類型的內容各歸其位。

### 👷建議的結構
```
my-notes/
├── README.md          ← 主頁目錄（保持簡潔）
├── notes/             ← 純文字筆記 (.md)
│   ├── github-basics.md
│   └── automation.md
├── pages/             ← 視覺化 HTML 頁面
│   ├── intro.html
│   ├── charts.html
│   └── navbar.html
└── notebooks/         ← 程式碼筆記 (.ipynb)，有需要再建
```
### ⚠️ GitHub 不能直接建立空資料夾，一定要「資料夾 + 檔案一起建」
1. 進到你的 repository（專案頁面）
2. 點擊 Add file → Create new file
3. 例如：在檔名輸入：folder_name/README.md
4. 往下拉，隨便寫點內容（例如：# Python Notes）
5. 點 Commit changes

### 🤟三種主要檔案格式

| 格式 | 用途 | 適合場景 |
|------|------|----------|
| `.md` | 純文字筆記 | 觀念說明、學習紀錄、條列整理 |
| `.html` | 視覺化互動頁面 | 圖表、遊戲、有設計感的展示 |
| `.ipynb` | Jupyter Notebook | 程式碼 + 執行結果 + 說明混合 |

### ❓為什麼要分？

- 📁 **好找** — 不用滾動整個 repo 找一個檔案
- ✏️ **好維護** — 修改某一頁不影響其他頁
- 📖 **好閱讀** — README 保持簡潔，細節放各自的檔案
- 🔗 **好分享** — 每個頁面都有獨立的網址可以分享

> 💡 原則：README 是目錄，資料夾是章節，檔案是內容。


