# 意識純淨度檢測器 v1.42
### Consciousness Purity Scanner · 全球意識健康管理局

> 一個基於「思辨設計（Speculative Design）」與「設計虛構（Design Fiction）」的互動網頁藝術專案。

---

## 世界觀背景

2030 年，科學家發現「石油」是遠古好戰高等物種滅絕壓縮而成的「意識化石」。燃燒與使用石化產品會釋放「奈米級神經寄生物質」至大氣。吸入後大腦會被劫持，引發全球通膨恐慌與無休止的戰爭。在這個未來世界，人們像唾棄吸菸者一樣，集體排斥使用石化產品的人。

本作品以反烏托邦視角，諷刺人類對石化依賴的集體盲視。

---

## 專案特色

- **單一 HTML 檔案**，無需任何後端，開箱即用
- **四步驟互動流程**：歡迎頁 → 行為申報 → 神經掃描動畫 → 診斷報告
- **三級公民等級**：純淨公民 / 潛在帶原者 / 血肉載具
- 全 **Dark Mode**，CRT 掃描線 + Glitch 特效 + 霓虹光暈
- 使用 **Tailwind CSS** + **Lucide Icons** + **Google Fonts**

---

## 快速開始

### 方法一：直接開啟（最簡單）
```bash
# 下載後直接用瀏覽器開啟
open index.html
```

### 方法二：用 GitHub Pages 部署（推薦）

1. Fork 或 Clone 此 repo
2. 進入 repo 設定 → **Pages**
3. Source 選擇 `Deploy from a branch`
4. Branch 選 `main`，資料夾選 `/ (root)`
5. 儲存後等待約 1 分鐘，即可透過以下網址存取：
   ```
   https://<你的帳號>.github.io/<repo名稱>/
   ```

### 方法三：本地 HTTP 伺服器
```bash
# Python 3
python3 -m http.server 8080

# Node.js (需安裝 serve)
npx serve .

# 然後開啟 http://localhost:8080
```

---

## 檔案結構

```
├── index.html          # 主體：完整互動網頁（單一檔案）
└── README.md           # 本說明文件
```

---

## 技術棧

| 項目 | 說明 |
|------|------|
| HTML5 / CSS3 | 純前端，無框架依賴 |
| Tailwind CSS v3 | 透過 CDN 引入 |
| Lucide Icons | 透過 CDN 引入 |
| Google Fonts | Orbitron · Share Tech Mono · Rajdhani |
| Vanilla JavaScript | 互動邏輯，無第三方 JS 庫 |

> **注意**：CDN 資源需要網路連線才能正常顯示字型與圖示。若需離線使用，請參考下方「離線部署」章節。

---

## 離線部署

如需在無網路環境使用，請將以下 CDN 資源下載至本地：

```html
<!-- 替換 index.html 中的 CDN 連結為本地路徑 -->
<link href="./assets/tailwind.min.css" rel="stylesheet" />
<script src="./assets/lucide.umd.js"></script>
```

---

## 創作理念

本作品屬於**思辨設計（Speculative Design）**範疇，透過誇張的偽官方介面與荒誕的世界觀設定，反思：

- 人類對石化能源的深度依賴是否如同「成癮」？
- 若石化污染的後果「看得見」，社會規範會如何改變？
- 科技監控與公民健康評分系統的邊界在哪裡？

---

## 授權

MIT License — 自由使用、修改、散佈，請保留原始創作聲明。

---

*全球意識健康管理局 · GCA-UNIT-7F · 機密等級：OMEGA*
*「您今日的每一次石化消費，都在為遠古戰神注射興奮劑。」*
