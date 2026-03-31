# 🥪 Sandwich Calculator

Mobile-first Subway-style nutrition calculator with iOS-inspired UI.  
以手機體驗為核心、帶有 iOS 風格互動的 Subway 營養計算工具。

## 🚀 Live Demo

https://thom436.github.io/sandwichcalculator.com/

## ✨ Features

- Flavor picker with grouped modal list + kcal hints  
  主餐口味使用分組彈窗清單，可直接看到各口味熱量

- Real-time nutrition summary  
  即時計算總熱量（kcal）與蛋白質（g）

- Add-ons flow optimized for mobile  
  加料支援快速新增、替換、刪除，流程更直覺

- Two-sauce support with auto split logic  
  支援第二種醬料，兩種醬料會自動平分熱量

- Optional sauce mode  
  可不選醬料（No sauce），不影響主餐與加料計算

- Dark mode + iOS-like motion feedback  
  深色模式與按鈕/切換動畫，提升操作手感

## 🧮 Calculation Rules

- Base: selected 6" sandwich
- Double meat: adds corresponding add-on nutrition (if available)
- Add-ons: summed by selected items
- Sauces:
  - 1 sauce: full sauce kcal
  - 2 sauces: each counted as 1/2
  - No sauce: 0 kcal from sauces

## 🛠️ Tech

- Vanilla HTML / CSS / JavaScript
- Static hosting via GitHub Pages

## 📦 Local Development

Open `index.html` directly in browser, or run a local static server.

Example:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## ⚠️ Disclaimer / 聲明

This is an independent tool and is not affiliated with SUBWAY®.  
Nutrition values are estimates and may vary by store and preparation.

本工具為非官方計算器，與 SUBWAY® 無關。  
營養數據為估算值，可能因門市與製作方式有所差異。

Nutrition source: [SUBWAY Taiwan official nutrition page](https://subway.com.tw/GoWeb2/include/meals-nutrition.html).  
營養資訊來源：[SUBWAY 台灣官方營養資訊](https://subway.com.tw/GoWeb2/include/meals-nutrition.html)。  
Data version: 2026-03-31 (manually curated).  
資料版本：2026-03-31（手動整理）。
