# ESG 綱站（專案藍圖）

> 本檔為跨 Agent 通用的專案藍圖（AGENTS.md 開放標準）。任何 Agent 的每個 session 都應先讀本檔＋`handoff.md`。

## 專案簡介
建多室廣（ESG PT）官方網站，專為台灣製造業與中小企業打造的一站式綠色空間升級展示平台。

## 線上展示網址
- GitHub Pages：https://garfiwang.github.io/esg-website/
- 原參考站：https://www.esg4u.tw

## 目標與路線圖
- [x] 階段一：網站架構與需求規劃（爬梳並解構 esg4u.tw 核心內容、團隊資歷與 8 大經典案例）
- [x] 階段二：前端頁面開發與介面設計（採用純靜態高質感 RWD 架構，包含深淺主題調性、Lightbox 檢驗報告放大、預約諮詢表單）
- [x] 階段三：功能測試與發布部署（下載全部 44 個高解析度圖檔與素材，部署至 GitHub Pages）

## 資料夾結構
```
ESG 綱站/
├── .gitignore          # Git 忽略設定檔
├── AGENTS.md           # 專案藍圖（本檔）
├── assets/
│   └── images/         # 網站完整 44 項圖片、團隊人像與臨床檢驗數據圖檔
├── handoff.md          # 交接檔
└── index.html          # 現代化純靜態前端主頁（部署至 GitHub Pages）
```

## 同步層級（本專案初始化至第 3 層級）

| 層級 | 平台 | 位置 | 讀取時機 |
|------|------|------|---------|
| L1 | 本地（GDrive） | `AGENTS.md`＋`handoff.md` | 每個 session |
| L2 | GitHub | https://github.com/garfiwang/esg-website（GitHub Pages: https://garfiwang.github.io/esg-website/） | 指定時 |
| L3 | Obsidian | `[Project] ESG 綱站/專案工作流程.md` | 有需要時 |

## 工作約定
- 任何 Agent、任何電腦：**開工先讀 `handoff.md`，收工必更新 `handoff.md`**
- 修改共用檔案前先讀最新內容，避免覆蓋其他 Agent 的變更
- 所有回應與文件使用繁體中文
- 修改前先確認計畫，優先保留原有資料結構
