# ESG 綱站（專案藍圖）

> 本檔為跨 Agent 通用的專案藍圖（AGENTS.md 開放標準）。任何 Agent 的每個 session 都應先讀本檔＋`handoff.md`。

## 專案簡介
建構專案網站。

## 關鍵時程
<!-- 格式：- 事件名稱：日期（說明）；沒有就留白 -->

## 目標與路線圖
<!-- 用 checklist 追蹤，收工技能會更新這裡 -->
- [ ] 階段一：網站架構與需求規劃
- [ ] 階段二：前端頁面開發與介面設計
- [ ] 階段三：功能測試與發布部署

## 資料夾結構
```
ESG 綱站/
├── .gitignore          # Git 忽略設定檔
├── AGENTS.md           # 專案藍圖（本檔）
└── handoff.md          # 交接檔
```

## 同步層級（本專案初始化至第 3 層級）

| 層級 | 平台 | 位置 | 讀取時機 |
|------|------|------|---------|
| L1 | 本地（GDrive） | `AGENTS.md`＋`handoff.md` | 每個 session |
| L2 | GitHub | https://github.com/garfiwang/esg-website | 指定時 |
| L3 | Obsidian | `[Project] ESG 綱站/專案工作流程.md` | 有需要時 |

## 工作約定
- 任何 Agent、任何電腦：**開工先讀 `handoff.md`，收工必更新 `handoff.md`**
- 修改共用檔案前先讀最新內容，避免覆蓋其他 Agent 的變更
- 所有回應與文件使用繁體中文
- 修改前先確認計畫，優先保留原有資料結構
