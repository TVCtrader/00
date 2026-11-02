# Seoul Trip 2026 | 首爾七日互動行程

**日期：** 2026-11-22 至 2026-11-28（七日）
**目的地：** 弘大、延南洞、望遠、聖水洞、恩平、北村、景福宮、乙支路、龍山、新龍山、三角地、漢南洞。

## 開啟網站

GitHub Pages 啟用後網址：
https://tvctrader.github.io/00/seoul-trip-2026/

倘未啟用 Pages，請前往 https://github.com/TVCtrader/00/settings/pages

1. Build and deployment > Source: **Deploy from a branch**。
2. Branch: **main**；folder: **/(root)**。
3. **Save**。公開網頁路徑為本目錄 /seoul-trip-2026/。

## 四個主要檔案

- `index.html` — 網頁入口
- `style.css` — 手機／電腦樣式
- `data.js` — 七日行程、食店、影片、弘大30間購物及候補收藏的初始資料
- `app.js` — 資料搜尋、編輯、拖曳、跨日移動、備份／還原

## 互動功能

- 每一項以獨立 BLOCK 顯示，包含韓文地址、Google Maps、Naver Map、來源及備註。
- 可自由新增、編輯、刪除、複製、移往其他日期；電腦拖曳及手機升降排序。
- 餐廳、弘大五區30間店舖及未安排資料有獨立分類。
- 個人編輯自動保存於該瀏覽器的 localStorage；**不會同步至其他手機／朋友帳戶**。
- 「匯出JSON」備份資料；「匯入JSON」可以將修改後行程傳到朋友手機。
- 「列印」可存PDF供離線參考。

## 分享與保密

本公開資料集已省略私人 Gmail、Airbnb 精確地址及訂單編號。影片未提供店名的資料標示為「待核實」，地址與營業資訊可能變動。

如希望所有朋友在同一網站自動看見協作修改，需要另配雲端資料庫／登入／權限控制。這個純靜態版本沒有跨使用者同步。
