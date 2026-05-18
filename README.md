# Ben Chang - Personal Brand Website

## 部署指南

此為 Ben Chang 個人品牌網站的靜態部署版本，可直接部署到 Cloudflare Pages、GitHub Pages 或其他靜態網站託管服務。

### 檔案結構

```
├── index.html           # 主頁面
├── assets/              # 靜態資源（CSS、JS）
│   ├── index-*.css      # 樣式表
│   └── index-*.js       # JavaScript 應用
├── _redirects           # Cloudflare Pages 路由規則
├── .nojekyll            # GitHub Pages 標記
└── README.md            # 本檔案
```

### 部署到 Cloudflare Pages

1. 將此資料夾內容上傳到 GitHub 倉庫
2. 在 Cloudflare Pages 中連接 GitHub 倉庫
3. 設定建置命令為空（已預先建置）
4. 設定發佈目錄為 `./`（根目錄）
5. 部署完成

### 部署到 GitHub Pages

1. 將此資料夾內容上傳到 GitHub 倉庫的 `gh-pages` 分支
2. 在 GitHub 倉庫設定中啟用 GitHub Pages
3. 選擇 `gh-pages` 分支作為發佈來源
4. 部署完成

### 部署到其他靜態託管服務

此為標準靜態網站，可部署到：
- Vercel
- Netlify
- AWS S3 + CloudFront
- Azure Static Web Apps
- 任何支援靜態網站的服務

### 技術棧

- React 19
- Tailwind CSS 4
- Vite 7
- shadcn/ui

### 功能特性

✓ 響應式設計（支援桌面、平板、手機）
✓ 手機版漢堡選單導航
✓ 頁面載入淡入動畫
✓ AI 系統架構示意圖
✓ McKinsey/Deloitte 顧問風格設計
✓ 深黑色、深灰色、米白色配色方案

### 聯絡方式

- Email: gavinchang0201@gmail.com
- Phone: 0935-201542
- LinkedIn: https://www.linkedin.com/in/ben-chang-ai/
- Facebook: https://www.facebook.com/aiflot

---

© 2024 Ben Chang. All rights reserved.
