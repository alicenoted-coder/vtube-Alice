# Codex 對話紀錄：建立 vtube-Alice 專案資料庫

- 日期：2026-09-21
- 時區：Asia/Taipei
- Repository：https://github.com/alicenoted-coder/vtube-Alice
- 紀錄範圍：使用者與 Codex 可見的對話內容；不包含系統內部指令或隱藏資訊

## 對話

### 使用者

> [@GitHub] https://github.com/alicenoted-coder/vtube-Alice

### Codex

> 已收到 GitHub repo：`alicenoted-coder/vtube-Alice`。
>
> 你希望我幫你做什麼？例如：整理專案架構、檢查程式碼、修 Bug、實作功能，或建立 PR？

### 使用者

> 現在這個對話的資料，我想都放在這個repo 中

### 使用者

> [@Composio]
>
> 這是我想要做的vtube 相關資料；  
> 我想知道，我現在有素材圖  
> 接下來要如何進行vtube?

### Codex

建議以 2D Live2D 路線進行：先確認素材圖是否為分層 PSD；若是扁平 PNG／JPG，先拆件與補畫；接著使用 Live2D Cubism 完成模型綁定，匯入 VTube Studio 做臉部追蹤，最後由 OBS 錄影或直播。

完整流程、素材分層清單與下一步已整理至：

- [從素材圖到 VTuber：Alice 的製作路線](../guides/vtube-from-artwork-roadmap.md)

目前最需要的下一份資料是原始素材圖。收到圖片後，可進一步製作素材可用性檢查、拆件清單、補畫區域、PSD 命名表與第一版驗收標準。

## 已確認的工作方式

- vtube-Alice 相關資料集中保存在此 repository。
- 對話紀錄使用日期化 Markdown 檔案，放在 `docs/conversations/`。
- repository 為公開狀態，因此不寫入密碼、API Key、Token、個資或機密資訊。
- 後續若對話產生程式碼、產品規劃或其他文件，依內容建立清楚的資料夾分類。
