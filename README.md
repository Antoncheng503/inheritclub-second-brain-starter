# 打造第二大腦

AI 工作記憶｜二代學入門教材

這份 GitHub 教材包含空白筆記、示意案例與 AI 讀取說明。把下方指令交給能在你已授權資料夾寫檔的 AI 助手，就能依文件建立自己的第二大腦。

## 第一次使用

把以下文字貼給你的 AI 助手：

```text
請讀取這份教學：
https://raw.githubusercontent.com/Antoncheng503/inheritclub-second-brain-starter/main/第二大腦建立教學.md

在目前已授權的新資料夾內，依照「給 AI 的建立與驗證流程」建立 ObsidianVault。
不要覆寫既有筆記，不要複製我其他專案的設定、金鑰或個人資料。
請驗證檔案後，告訴我在 Obsidian 要開啟哪個資料夾。
```

你不用手動下載 ZIP；AI 仍須能讀取這份文件並在本機建立筆記。若工具不能上網或寫檔，改看完整教學的手動方式。

建立後安裝 [Obsidian](https://obsidian.md/download)，選「開啟資料夾為儲存庫」，指定 AI 實際建立的 `ObsidianVault`。打開 `00-開始這裡.md`，填一條自己的工作規則。

完整操作與「請 AI 協助設定」的指令見 [第二大腦建立教學.md](第二大腦建立教學.md)。

## 檔案分工

- `第二大腦建立教學.md`：給學員看的操作，以及給 AI 執行的建立／驗證流程。
- `ObsidianVault/`：在 Obsidian 開啟的資料夾。
- `ObsidianVault/AGENTS.md`：支援此入口的 AI 助手讀取規則。
- `ObsidianVault/CLAUDE.md`：指向同一份規則，避免維護兩套。

這個入門包不含 Obsidian 安裝程式、不含第三方外掛，也不附 Anton 的私人資料。AI 不需要 API 金鑰就能閱讀提供的文字；使用 AI 工具仍須有該工具適用的帳號或方案。

教材首頁：https://github.com/Antoncheng503/inheritclub-second-brain-starter

本教材只包含教學與範本，沒有設定公開授權條款。學員自己的筆記留在自己的資料夾，不會因使用本教材就傳回這個公開 repo。
