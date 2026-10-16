# 法身實相實修

法身實相修行輔助工具：凝視攝受、圓光冥想、六根帶動引導、實證日誌，並可請 AI 實相導師解答。

**線上使用**：https://kftseng2oo1.github.io/dama/

## 分頁與功能
- **凝視**：載入上師或法相圖片，定位眉心、開啟放光特效，計時凝視並記錄體會
- **圓光**：調整圓光的位置、大小、顏色（金、銀、橘黃綠），進行對看連結
- **帶動**：六項感官（視、聽、嗅、觸、味、整合）語音引導，可調節奏與靜默時間
- **心法**：顯化能力儀表板（雷達圖）、請問實相導師（AI）、導引知識庫（圓光不穩、對看要領、眉心放光…）
- **軌跡**：修行紀錄與統計

## 技術與依賴
- 單檔 HTML PWA（`index.html` 內含全部 HTML/CSS/JS），`manifest.json` + `sw.js` 提供安裝到主畫面與離線快取。
- AI：`claude-haiku-4-5-20251001`，經 `twinklehub.kftseng2oo1.workers.dev/v1/messages` 代理
- `speechSynthesis` 語音引導、Wake Lock 保持亮屏
- 圖片與紀錄存在本機，圖片會先壓縮以節省空間

## 相關 repo
- [buddha](https://github.com/kftseng2oo1/buddha)：阿拉燈佛法心靈導師
