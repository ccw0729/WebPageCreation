# Web Page Creation DEMO

兩個用來展示「AI 生成網頁」能力的單檔範例，全部是純 HTML / CSS / JavaScript，不需要任何框架或建置步驟，上傳到 GitHub Pages 即可展示。

| 檔案 | 類型 | 展示重點 |
|---|---|---|
| `index.html` | 入口頁 | 兩個 Demo 的導覽卡片 |
| `demo1-nebula-cafe.html` | 品牌形象 Landing Page | 互動星空粒子、滑鼠連線、3D 傾斜卡片、打字機效果、數字跳動、捲動淡入、點擊星星爆炸 |
| `demo2-aurora-dashboard.html` | 即時數據戰情室 Dashboard | 即時串流折線圖、雷達掃描、甜甜圈圖、長條圖、環形儀表、事件日誌、極光背景 |

## 部署到 GitHub Pages

1. 在 GitHub 建立新的 repository（例如 `web-demo`），設為 Public。
2. 把這 4 個檔案上傳到 repository 根目錄（Add file → Upload files）。
3. 進入 **Settings → Pages**，Source 選 **Deploy from a branch**，Branch 選 `main`、資料夾選 `/ (root)`，按 Save。
4. 約 1 分鐘後即可開啟：`https://<你的帳號>.github.io/web-demo/`

## 課堂示範用 Prompt

可以在課堂上直接用以下 Prompt 現場生成，再和成品對照：

**Demo 1｜星雲咖啡**
> 幫我做一個虛構品牌「星雲咖啡 NEBULA」的單頁形象網站，單一 HTML 檔、不使用框架。風格是宇宙霓虹＋玻璃擬態：背景要有會跟著滑鼠互動的星空粒子、漂浮的漸層光暈；標題用流動漸層文字加打字機副標；菜單用 4 張會隨滑鼠 3D 傾斜的卡片；加一條斜向跑馬燈、一區會跳動的統計數字、捲動時元素淡入，最後的 CTA 按鈕點擊會噴出星星。要支援手機版。

**Demo 2｜AURORA 戰情室**
> 幫我做一個「智慧城市即時戰情室」Dashboard，單一 HTML 檔、不用任何圖表函式庫，全部用 Canvas 和 SVG 自己畫。科幻霓虹風：深色網格背景、極光旋轉光暈、掃描線。內容包含 4 個會跳動的 KPI 卡片（附迷你走勢圖）、即時串流的多線折線圖、雷達掃描動畫、能源組成甜甜圈圖、各行政區長條圖、3 個環形儀表、自動滾動的事件日誌、即時時鐘。資料用亂數模擬，每幾秒更新一次。RWD 響應式。

> 註：頁面內的品牌與數據皆為虛構示範用途。
