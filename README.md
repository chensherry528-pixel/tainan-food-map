# 台南慢食地圖｜GitHub Pages 入門版

這是靜態美食搜尋網站，支援台南東區、北區、中西區、安平區、永康區，並提供關鍵字搜尋、料理分類及 Google Maps 搜尋連結。

## 注意
目前內建的是示範資料，不是已查證的真實店家清單。正式公開前請逐筆替換並核實店名、地址、價位、營業時間及資料使用權。

## GitHub Pages 部署
1. 進入 Repository 的 **Settings → Pages**。
2. 在 **Build and deployment** 的 **Source** 選 **Deploy from a branch**。
3. Branch 選 `main`，資料夾選 `/(root)`，按 **Save**。
4. 等待部署完成，在 Pages 設定頁查看公開網址，通常是 `https://你的GitHub帳號.github.io/tainan-food-map/`。

## 編輯店家資料
在 `index.html` 搜尋 `const DATA=[`，依照物件格式新增或修改項目。行政區使用「東區、北區、中西區、安平區、永康區」；分類使用頁面選單中的分類名稱。

## 地圖資料
目前使用 Google Maps URLs 開啟搜尋，不需要 API Key。若未來要自動取得店家評分、照片或營業狀態，需另外評估 Google Places API、帳務與金鑰限制。
