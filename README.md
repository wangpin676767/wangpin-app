# 王品工作台｜原始碼公開版

Windows x64 多模型桌面工作台，最新公開版本 **1.9.103**。

- [下載安裝檔、完整原始碼 ZIP 與 SHA256](https://github.com/wangpin676767/wangpin-app/releases/tag/v1.9.103)
- [官方下載頁](https://www.wangpin67.com/p/wangpin-app.html)

## 1.9.103

 保留 wangpinplan、skill／Markdown／MCP、System Prompt、網頁模型與帳號管理、Rust 加速。使用獨立安裝及資料目錄，可與自用版並存。模型服務需自行登入並使用自己的額度。

## 安裝與原始碼

1. 關閉舊開源版，至 Release 的 Assets 下載 `.exe`。
2. 下載 `SHA256SUMS.txt`，用 `Get-FileHash -Algorithm SHA256` 核對。
3. 完整應用程式原始碼請下載 Assets 的 **`wangpin-source-1.9.103.zip`**，包含 JavaScript、Rust、建置工具及測試。建置步驟與第三方授權見 ZIP 內 README、THIRD_PARTY_NOTICES.md。

**目前儲存庫主要提供版本說明與下載；GitHub 自動產生的 Source code ZIP 只含此儲存庫內容，不是完整應用程式。完整原始碼以附加的 ZIP 為準。**

安裝檔 SHA256：`62f572c2c4f95e33cc4694c85a7d275182c7ff5983981470db50e4c293c099ae`。安裝檔未簽章。

## 驗證

80 項相關測試及 15 項包內操作驗證通過；未做真實模型推論或壓力測試。自用版原始碼未更動。

## 授權狀態

本次已公開完整原始碼，但作者尚未指定本專案授權條款；不要假設已取得自由修改及再散布的開源授權。第三方元件依各自授權。

## 問題回報

請使用 Issues，附版本、Windows 版本及重現步驟；不要公開 API 金鑰、Cookie、登入資料或私人對話。
