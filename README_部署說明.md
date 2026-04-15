# 波段分析靜態網站部署說明

此資料夾已可直接作為靜態網站部署。

## 內容
- `index.html`：總覽首頁
- `dashboards/`：各股儀表板
- `analysis/`：各股文字分析

## 部署方式
### GitHub Pages
1. 建立一個新的 GitHub repository
2. 將此資料夾內容全部上傳到 repository 根目錄
3. 到 GitHub Pages 設定頁，選擇從 `main` branch 部署

### Netlify / Vercel / Cloudflare Pages
1. 新建站點
2. 上傳這個資料夾或連接含有此資料夾內容的 repo
3. 設定輸出目錄為根目錄 `/`
4. 不需要 build command

## 本機預覽
在此資料夾內執行：

```bash
python3 -m http.server 8000
```

再打開：
`http://localhost:8000`
