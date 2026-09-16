# 待機時鐘與跑馬燈

可直接部署到 GitHub Pages，並在 iPhone 加到主畫面當作獨立 App 使用。

## 上傳到 GitHub

1. 在 GitHub 建立新的 repository，將這個資料夾內的所有檔案上傳。
2. 到 repository 的 **Settings → Pages**。
3. 在 **Build and deployment** 選擇 `Deploy from a branch`，Branch 選 `main` 與 `/ (root)`，再按儲存。
4. 等待 GitHub 顯示網站網址，使用 iPhone Safari 開啟該網址。

## 加到 iPhone 主畫面

在 Safari 點選底部的「分享」按鈕，選擇 **加入主畫面**，名稱可保留「待機時鐘」。主畫面會使用 `icons/icon-180.png` 作為圖示，開啟時會以獨立 App 方式顯示。

## 重要檔案

- `index.html`：主網頁
- `site.webmanifest`：App 名稱、主題與 Android／瀏覽器圖示設定
- `sw.js`：離線快取設定
- `icons/icon-180.png`：iPhone 主畫面圖示
- `icons/icon-192.png`、`icons/icon-512.png`：PWA 圖示
