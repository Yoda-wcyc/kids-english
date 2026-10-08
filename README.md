# kids-english（舊網址轉址）

小朋友學習站已經搬到 **https://yoda-wcyc.github.io/Kids-Station/**（repo：`Yoda-wcyc/Kids-Station`）。

這個 repo 只負責把舊網址 `https://yoda-wcyc.github.io/kids-english/...` 導到新網址的對應位置：

- `index.html` 與 `404.html` 內容相同：用 JS 把網址路徑開頭的 `/kids-english` 換成 `/Kids-Station`，保留 `?查詢字串` 與 `#hash`，再 `location.replace` 過去。
  - 例：`/kids-english/math/balance.html` → `/Kids-Station/math/balance.html`；`/kids-english/#s/英文` → `/Kids-Station/#s/英文`。
- 後備：關掉 JS 時，3 秒後 meta refresh 到新網址首頁；頁面上也有手動連結。
- GitHub Pages：main 分支根目錄。

不要在這裡放學習站的內容，改內容請到 Kids-Station。
