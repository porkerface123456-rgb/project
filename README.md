# 專案作品集 (Project Portfolio)

一個簡潔、美觀且具備響應式設計（RWD）的現代化前端專案作品集入口首頁，整合了數據分析、教育科技與生產力工具等互動式 Web 專案。

---

## 🌟 專案總覽

本作品集首頁 (`index.html`) 採用現代化 **Glassmorphism（玻璃擬態）** 視覺設計風格，搭配深色漸層光暈與微互動特效，提供流暢的瀏覽與專案切換體驗。

### ✨ 首頁核心特色

- 📱 **RWD 響應式佈局**：支援桌面螢幕、平板與手機等不同尺寸裝置。
- 🔍 **即時關鍵字搜尋**：支援依專案名稱、技術標籤或功能描述即時篩選。
- 🏷️ **分類標籤過濾**：可快速切換「全部專案」、「數據分析」、「教育學習」與「生產力工具」。
- 🚀 **純前端輕量架構**：無需建置編譯工具，開箱即用。

---

## 📁 收錄專案介紹

### 1. 數位媒體廣告成效數據儀表板 (`DMADAna.html`)
- **類型**：數據分析與可視化 / 數位行銷
- **特色**：
  - 支援 Excel / CSV 檔案即時解析與匯入（SheetJS）。
  - 使用 Apache ECharts 繪製多維度互動數據圖表。
  - 涵蓋廣告成效漏斗分析、ROI / ROAS 效益評估與多平台指標對比。
- **技術棧**：HTML5, Tailwind CSS, SheetJS (xlsx), Apache ECharts, Font Awesome

---

### 2. ⭐️ 星星老師陪你讀_專屬學習導航 (`Studenttest.html`)
- **類型**：教育科技 (EdTech) / 學習診斷
- **特色**：
  - 學生測驗成績與學力落點即時診斷。
  - 依據各科表現生成強弱項分析報告。
  - 提供個人化專屬讀書計畫與補強建議。
- **技術棧**：HTML5, Tailwind CSS, Vanilla JavaScript

---

### 3. 游老大的計時器 (`firecountdown.html`)
- **類型**：沉浸式生產力工具 / 番茄鐘計時器
- **特色**：
  - 整合 Tone.js 合成擬真篝火白噪音音效。
  - 復古像素字體風格（DotGothic16 / Press Start 2P）與多種主題切換。
  - 支援全螢幕專注模式、自訂倒數預設時間。
  - 計時結束時觸發 Canvas Confetti 彩帶慶祝動畫。
- **技術棧**：HTML5, Tailwind CSS, Tone.js, Canvas Confetti, Google Fonts

---

## 📂 專案目錄結構

```text
project/
├── .gitignore             # Git 忽略設定
├── README.md              # 專案說明文件
├── index.html             # 作品集首頁入口
├── DMADAna.html           # 數位媒體廣告成效數據儀表板
├── Studenttest.html       # 星星老師陪你讀_專屬學習導航
└── firecountdown.html     # 游老大的計時器
```

---

## 🚀 如何使用與開啟

### 方法一：直接點擊開啟
使用任何現代瀏覽器（Chrome, Safari, Edge, Firefox 等），直接雙擊開啟 `index.html` 即可開始瀏覽所有專案。

### 方法二：透過本機 HTTP 伺服器啟動（推薦）
若需要更完整的本機預覽環境，可使用以下任一方式：

**使用 Python 內建伺服器：**
```bash
# Python 3
python3 -m http.server 8000
```
開啟瀏覽器前往 `http://localhost:8000`

**使用 Node.js / npx serve：**
```bash
npx serve .
```

---

## 📄 授權與聲明

本專案集僅供個人作品展示與學習用途。
