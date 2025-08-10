# manythanks – Online Package (v8 · Clean + Simple Card)

**根網址**：https://nuncstans0321.github.io/manythanks/
**授權碼資料夾**：/1718345765717998104111112117121/index.html
**媒體資料夾**：/assets/

本包為「乾淨版本」：無示範連結、無示範影片，僅附一張 `assets/card.png` 的 **Simple Card**，
讓頁面可以正常打開。日後只要替換 /assets 內容即可。

## 替換方式
- 影片：上傳 `/assets/card.mp4`
- 圖片：上傳 `/assets/card.png`、或 `.jpg/.webp`
- PDF：上傳 `/assets/card.pdf`
- YouTube：新增 `/assets/card.json` 或 `/assets/card.url` 指向影片
  - `card.json` 範例：
    {
      "type": "youtube|video|image|pdf|auto",
      "src": "你的連結或路徑",
      "title": "（可選）標題"
    }
  - `card.url`：檔案內容為一行 URL（YouTube / 影片 / 圖片 / PDF 皆可）

> 優先序：`card.json` > `card.url` > 檔名偵測（mp4 → png → jpg → jpeg → webp → gif → pdf）
