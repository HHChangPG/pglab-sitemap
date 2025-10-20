# PGLab Google Sites — Sitemap（GitHub Pages 託管）

**你的實際 Sitemap 連結：**
- XML：https://HHChangPG.github.io/pglab-sitemap/sitemap.xml
- TXT：https://HHChangPG.github.io/pglab-sitemap/sitemap.txt

## 要做什麼
1. 在 GitHub 建立公開倉庫：**pglab-sitemap**
2. 將本資料夾的檔案上傳到倉庫根目錄（`/`）。
3. 到 **Settings → Pages**：
   - Source：**Deploy from a branch**
   - Branch：**main / root**
4. 發佈後，用瀏覽器開啟：
   - https://HHChangPG.github.io/pglab-sitemap/sitemap.xml
   - https://HHChangPG.github.io/pglab-sitemap/sitemap.txt

## 在 Google Search Console 提交（跨網站提交）
需要驗證兩個 URL-prefix 屬性：
- A：**Google Sites** → `https://sites.google.com/view/pglab-hhchang-ncku/`
- B：**GitHub Pages** → `https://HHChangPG.github.io/`

接著到 **Google Sites 的屬性 → Sitemaps**，提交：
- https://HHChangPG.github.io/pglab-sitemap/sitemap.xml

## 同步為重點頁送索引（URL 檢查）
依序貼上以下網址→若未編入索引則按「要求編入索引」：
- https://sites.google.com/view/pglab-hhchang-ncku/home
- https://sites.google.com/view/pglab-hhchang-ncku/principal-investigator
- https://sites.google.com/view/pglab-hhchang-ncku/research-projects
- https://sites.google.com/view/pglab-hhchang-ncku/publications
- https://sites.google.com/view/pglab-hhchang-ncku/activity
- https://sites.google.com/view/pglab-hhchang-ncku/people
- https://sites.google.com/view/pglab-hhchang-ncku/contact-us

## 更新 Sitemap
- 新增頁面時：把新網址加到 `sitemap.xml` 與 `sitemap.txt`，推送到 main 分支即可。
- 可用：`https://www.google.com/ping?sitemap=https://HHChangPG.github.io/pglab-sitemap/sitemap.xml` 提醒 Google 抓取。

產生時間：2025-10-20T15:36:30.733380Z
