# 姜秉勳 Ping-Hsun Chiang — 個人履歷網站

一個以 **個人形象展示** 與 **作品集呈現** 為核心的靜態履歷網站，目標是透過簡潔而完整的數位名片，讓求職方、學術機構或合作夥伴能快速了解個人背景、技術能力與專案成果。本專案以 Hugo 靜態網站產生器為基礎，結合客製化版面與 GitHub Actions 自動化部署流程，打造出兼顧內容深度與瀏覽體驗的專業履歷網站。

## Website
- Live Site: [https://ping-hsun-chiang.github.io/personal-website/](https://ping-hsun-chiang.github.io/personal-website/)

## Project Overview
本專案以 Hugo 靜態網站產生器搭配 PaperMod 主題為基底，並針對履歷場景進行深度客製化，打造出單頁滾動式的數位履歷。除了基本的個人資訊呈現外，亦加入了結構完整的各功能區塊，與實際業界履歷投遞場景高度吻合：

- 個人簡介與技術能力一覽
- 學歷、工作 / 研究經歷時間軸
- 個人專案作品集（含連結與技術標籤）
- 排球球隊戰績記錄的獨立子頁
- GitHub Actions 自動化部署，推送即上線

這讓專案不只是靜態的個人頁面，而是一個具備完整資訊架構、自動化維運流程的專業數位履歷平台。

## Main Features

### 1. 個人形象展示
- 大頭貼、姓名、職涯定位標語
- GitHub、LinkedIn 快速連結按鈕
- 完整自我介紹，涵蓋研究方向、工程能力與開發哲學

### 2. 技能清單
- 依類別分組展示：程式語言、AI / 機器學習框架、資料分析工具、統計建模、工程與開發工具、雲端 / 部署服務

### 3. 學歷與工作 / 研究經歷
- 時間軸格式呈現學術背景與工作經歷
- 涵蓋研究助理、AI 實習工程師、國際交換、課程助教等多元角色

### 4. 個人專案作品集
- 每項專案含日期、名稱、描述與技術標籤
- 支援 GitHub 連結導出，部分私有專案另有說明
- 涵蓋深度學習、API 自動化、前端全端、統計研究等多樣類型

### 5. 排球球隊頁面
- 獨立子頁展示球隊「鞋槓青年」的歷屆賽事紀錄
- 包含賽事名稱、日期、賽果與參賽成員
- 支援單張大圖、雙欄並排、三欄並排等多種相片版面配置

### 6. 自動化部署
- 透過 GitHub Actions 工作流程，每次推送至 `main` 分支即自動觸發建置與部署
- 使用 Hugo Extended 版本進行最小化（minify）建置
- 網站即時發布至 GitHub Pages，維護零手動操作

## Technologies Used
- **Hugo**（靜態網站產生器）
- **PaperMod 主題**（客製化 Layout 與 CSS）
- **HTML5 / CSS3**（版面客製化）
- **TOML**（Hugo 設定檔）
- **Markdown**（內容撰寫）
- **GitHub Actions**（CI/CD 自動化部署）
- **GitHub Pages**（靜態網站托管）

## Author
**Ping-Hsun Chiang（姜秉勳）**  
GitHub: [Ping-Hsun-Chiang](https://github.com/Ping-Hsun-Chiang)  
LinkedIn: [andrew-chiang-a99a94321](https://www.linkedin.com/in/andrew-chiang-a99a94321/)
