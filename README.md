# Raybird 的個人網站

原生 HTML 與 CSS，沒有框架、套件依賴或建置步驟。需要互動時再加入原生 JavaScript。

## 本機預覽

在專案根目錄執行：

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

瀏覽 <http://127.0.0.1:8000>，按 `Ctrl+C` 停止。也可以直接用瀏覽器開啟 `index.html`。

## 編輯

- `index.html`：頁面內容與語意結構。
- `styles.css`：版面、色彩與字型；主要色彩集中在 `:root`。
- `.nojekyll`：讓 GitHub Pages 直接提供靜態檔案。

首頁包含個人介紹、分類作品，以及筆記與生活。專案介紹直接寫在 HTML，更新時一併確認 GitHub 連結與公開 README 內容。

## GitHub Pages

發布來源使用 `main` 分支的根目錄。在儲存庫的 **Settings → Pages** 選擇 **Deploy from a branch**、`main` 與 **/ (root)**；推送到 `main` 後由 GitHub Pages 自動發布，不需要建置指令。

網站網址：<https://raybird.github.io/>。
