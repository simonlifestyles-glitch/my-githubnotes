# 📓 GitHub 使用筆記

> 給程式小白的 GitHub 入門筆記，從零開始也看得懂。

🔰 [GitHub 是什麼？（視覺化入門）](https://simonlifestyles-glitch.github.io/my-notes/intro.html)
📊 [圖解筆記（Branch 與功能說明）](https://simonlifestyles-glitch.github.io/my-notes/charts.html)
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
