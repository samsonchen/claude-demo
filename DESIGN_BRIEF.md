# Design Brief

## 店家資訊
- 名稱：麥吉肉羹
- 類型：餐廳（傳統肉羹小吃）
- 風格建議：請依店家類型與照片氛圍判斷（傳統台式小吃風格，親切樸實）

## 照片資產
- 店面外觀：1 張
- 室內環境：1 張
- 招牌品項：3 張
- 菜單照片：1 張（文字已辨識存於 menu.json）

## 頁面結構需求
1. Hero 區（店家名稱、標語、主視覺照片）
2. 關於我們（店家簡介、評分）
3. 菜單區（從 menu.json 以文字呈現，非圖片）
4. 品項展示（招牌品項照片）
5. 環境介紹（室內照片輪播）
6. 營業資訊（時間、電話、地址）
7. Google Maps 嵌入地圖
8. 頁腳

## 技術規格
- 純 HTML / CSS / JS（無需框架，方便 GitHub Pages 直接 hosting）
- 響應式設計（mobile-first）
- 照片資料來源：images/ 資料夾
- 菜單資料來源：data/menu.json（以 JavaScript 動態載入）
- 地圖嵌入：data/restaurant.json 的 embedUrl 欄位

## 部署目標
- GitHub Pages
- Repo：claude-demo
