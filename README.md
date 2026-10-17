# 王品工作台｜原始碼公開版

Windows x64 多模型桌面工作台，最新公開版本 **1.9.104**。

- [下載安裝檔、完整原始碼 ZIP 與 SHA256](https://github.com/wangpin676767/wangpin-app/releases/tag/v1.9.104)
- [官方下載頁](https://www.wangpin67.com/p/wangpin-app.html)

## 1.9.104

修正誤入全螢幕導致標題列、關閉按鈕與 Windows 工作列消失。停用 F11 全螢幕切換，保留最大化、還原及一般 Escape 行為。

保留 wangpinplan、skill／Markdown／MCP、System Prompt、網頁模型與帳號管理、Rust 加速；不包含王品agent腳本功能。模型服務需自行登入並使用自己的額度。

## 安裝與原始碼

1. 關閉舊開源版，至 Release 的 Assets 下載 `wangpin-Setup-OpenSource-1.9.104.exe`。
2. 下載 `SHA256SUMS.txt`，用 `Get-FileHash -Algorithm SHA256` 核對。
3. 完整程式請下載 **`wangpin-source-1.9.104.zip`**，包含 JavaScript、Rust、建置工具及測試；建置說明及第三方條款見 ZIP 內 README、THIRD_PARTY_NOTICES.md。

GitHub 自動產生的 Source code ZIP 僅對應儲存庫內容，完整應用程式原始碼以附加 ZIP 為準。

安裝檔 SHA256：`925f112b5cf99e1035853052632c84eaf33a10b5277046227cfc4dab596456a4`。安裝檔未簽章。

## 驗證

7 項針對性測試、5 項包內視窗驗證及 125 個產品檔案核對通過；未執行真實模型推論或壓力測試。

## 授權狀態

專案授權尚未指定，請勿假設已取得自由修改及再散布的授權；第三方元件依各自條款。

## 問題回報

請使用 Issues，附版本、Windows 版本及重現步驟；不要公開金鑰、Cookie、登入資料或私人對話。
