# 我的網頁作品集 (Personal Web Portfolio)

> 📱 專注於 **手機優先（Mobile-First）** 體驗的現代前端互動作品集。收錄各類實用工具、動態視覺與生活應用。

---

## 🌟 作品列表 (Projects)

### 1. 🎰 [大樂透好運發球機 (Lucky Lotto Popper)](tools/lucky-draw.html)
- **分類**：🛠️ 實用工具 (Tools)
- **簡介**：復古街機風格的互動式大樂透搖珠抽獎機，忠實模擬實體彩球在吹氣滾筒內的物理碰撞、浮動與噴射出球動畫。介面結合鮮豔霓虹色彩與即時合成器音效，每次開獎皆帶來滿滿儀式感與視聽震撼，支援一鍵搖號與中獎彩票存根生成。
- **核心技術**：
  - `HTML5 Canvas 2D API`（彩球物理碰撞運動渲染）
  - `Web Audio API`（自製音訊振盪器合成器，免外部音檔即時產生吹氣、滾珠與出球音效）
  - `requestAnimationFrame API`（流暢 60fps 運動物理與重繪）
  - `Tailwind CSS & CSS3 Keyframes`
  - `Touch & Pointer Events API`（行動端觸控支援）
- **應用場景**：尾牙春酒抽獎、直播粉絲互動開獎、課堂活動選號、彩券幸運號碼靈感模擬。

---

### 2. 🕰️ [沉浸式風景大時鐘 (Immersive Landscape Clock)](tools/clock.html)
- **分類**：🛠️ 實用工具 (Tools)
- **簡介**：極簡優雅的沉浸式風景大時鐘，精選全球高解析度自然絕景作為動態背景，支援 Ken Burns 微縮放與平滑淡入淡出切換。結合毛玻璃質感資訊面板、大字體時間顯示與多種自訂模式，無論放置於桌上立架或大螢幕展示皆賞心悅目。
- **核心技術**：
  - `Fullscreen API`（全螢幕專注時鐘模式，支援快捷鍵 `F`）
  - `Date & Timing API`（毫秒精確時鐘與每分鐘平滑換景）
  - `CSS3 Animations & Transitions`（Ken Burns 微動態縮放與 crossfade 轉場）
  - `Glassmorphism UI`（毛玻璃視覺面板）
  - `Keyboard Event API`（全螢幕與換景快捷鍵）
- **應用場景**：辦公桌面閒置平板/手機翻頁時鐘、專注讀書番茄鐘背景、客廳電視大螢幕環境氛圍鐘、演講會議倒數提示。

---

## 📂 專案目錄結構 (Directory Structure)

```text
myworks/
├── index.html            # 作品集首頁 (手機優先 Mobile-First 響應式架構)
├── tools/                # 實用工具專案
│   ├── lucky-draw.html   # 大樂透好運發球機
│   └── clock.html        # 沉浸式風景大時鐘
├── about/                # 關於我相關資料
│   └── images/
│       ├── avatar.png    # 個人頭像
│       └── aboutme.png   # 個人形象橫幅
├── apps/                 # 應用程式 (持續籌備中)
├── games/                # 互動遊戲 (持續籌備中)
├── art/                  # 數位藝術 (持續籌備中)
├── music/                # 音樂創作 (持續籌備中)
├── videos/               # 影音作品 (持續籌備中)
└── README.md             # 專案說明文件
```

---

## 🚀 快速開始與本地預覽 (Getting Started)

本專案採用純靜態前端技術構建，無須安裝額外依賴環境：

1. **直接開啟**：
   在瀏覽器中直接開啟 `index.html` 即可瀏覽作品集首頁。
2. **透過本機伺服器瀏覽**：
   ```bash
   # 使用 Python 內建伺服器
   python3 -m http.server 8000
   
   # 或使用 Node.js serve
   npx serve .
   ```
   開啟瀏覽器訪問 `http://localhost:8000`。

---

## 🌐 啟用 GitHub Pages 線上瀏覽

1. 將本倉庫 Push 至 GitHub。
2. 進入 GitHub 倉庫的 **Settings** > **Pages**。
3. 在 **Branch** 選擇 `main` 分支並設定目錄為 `/ (root)`，點擊 **Save**。
4. 稍候數分鐘即可透過 `https://rickjhang.github.io/myworks/` 線上瀏覽！

---

## 👤 作者 (Author)

- **GitHub**: [@rickjhang](https://github.com/rickjhang)
- **定位**：前端開發 · 互動體驗 · 行動優先設計

---

## 📄 授權條款 (License)

本專案採用 [MIT License](LICENSE) 授權。
