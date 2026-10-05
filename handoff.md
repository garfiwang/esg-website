# 交接檔（handoff.md）

> 任何 Agent、任何電腦接手前**必讀**；收工時**必更新**。本檔只放交接必需的精簡資訊，詳細脈絡放 Obsidian（若有 L3）。

## ⏯️ 目前做到哪
完成「建多室廣 ESG PT」官方網站的完整逆向工程與代碼重構：
1. 從原站 `esg4u.tw` 成功下載全部 44 個高解析度實景圖片、團隊人像與臨床實驗報告圖表至 `assets/images/`。
2. 採用純靜態現代 HTML5 + Tailwind CSS + Lucide Icons 架構，重構為零贅碼、毫秒級載入、全自適應（RWD）的現代化單頁網站。
3. 修正原網站 `noindex, nofollow` 導致 SEO 無法被 Google 收錄的重大缺陷，並修正副標「室廣一建永續鏈」之注音錯字。
4. 部署至 GitHub Pages：https://garfiwang.github.io/esg-website/。

## 🚦 目前狀態
已完成網站開發與測試，所有靜態資產與圖片鏈結均通過驗證，已推播至 GitHub 儲存庫並完成 GitHub Pages 發布。

## ➡️ 下一步
1. 觀察 GitHub Pages 上線後在各裝置上的顯示效果與載入速度。
2. 後續若需綁定自有網域名稱（如自訂 domain），可於 GitHub Pages 設定 CNAME。
3. 若需將諮詢表單串接真實後端或通知（如 Google 試算表、Email 或 LINE Notify），可進一步擴充表單處理邏輯。

## ⚠️ 注意事項
- 圖片均存放於本地 `assets/images/`，以相對路徑引用，確保離線或 GitHub Pages 均能正常加載。
- GitHub 儲存庫為公開（Public），以支援免費用戶的 GitHub Pages 託管。

## 🕐 最後更新
- 時間：2026-10-05 23:46
- 更新者：Antigravity @ Mac
- Git push：✅ 已推
