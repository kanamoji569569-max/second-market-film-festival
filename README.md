# 舊市尋味・第二市場專題影展 網頁專案 (Vibe Coding Prompt 說明)

本專案為逢甲大學行銷學系「網頁設計」期末作業成果，由學生 **松尾和磨（學號：d1429682）** 透過 AI Vibe Coding 協作完成。

## 一、專案主題與背景
- **專題題目**：大二「您自己的影展專題介紹」
- **企劃靈感**：改編自行銷系分組口頭報告《國家地理頻道：台中年輕人的神祕生態》，以幽默風趣的生態紀錄片視角，探討 18～24 歲台中在地年輕人重新認識「第二市場」歷史建築（六角樓）與傳統小吃之歷程。

## 二、Vibe Coding 核心 Prompt 指令紀錄

### 1. 架構設計與 SEO 設定 Prompt
> 「請根據《國家地理頻道：台中年輕人的神祕生態》劇本內容，規劃一個完整的影展專題網站。要求具備完全符合 HTML5 語意的導覽列（Navbar）、側邊欄（Sidebar）、頁尾（Footer），並採用三頁分頁架構（index.html 首頁、films.html 放映片單、info.html 活動與交通）。請加入完整的 SEO Meta Tags（包含 Title、Description、Keywords、Open Graph 社交分享設定）。」

### 2. CSS Grid 與 RWD 響應式佈局 Prompt
> 「請將 CSS 樣式完全獨立至 css/style.css 檔案中。色彩計畫採用國家地理經典黃（#ffcc00）與深灰黑質感設計。版面要求使用 CSS Grid System 實作電影卡片清單與雙欄佈局（內容區 + 側邊欄），並加入 @media 查詢實現 RWD 響應式設計，確保手機與行動裝置皆可流暢閱讀與排版。」

### 3. 實境影音與多媒體整合 Prompt
> 「請在首頁整合 HTML5 `<video>` 播放器嵌入團隊拍攝的《舊市尋味》前導宣傳短片，並將實地拍攝的第二市場招牌、六角樓與市場內部照片置於 `images/` 資料夾中引用；同時在活動與交通頁嵌入響應式 Google 地圖與放映場次表。」

## 三、技術特色與成果規範符合度
- [x] 導覽列、側邊欄、分頁架構（`index.html`、`films.html`、`info.html`）
- [x] 完整 SEO Meta 標籤設定
- [x] 獨立外部樣式表（`css/style.css`）
- [x] CSS Grid System 與 RWD 手持裝置響應式佈局
- [x] 實境照片與前導影片整合
- [ ] 
