# 我的財務小管家 v28 — Public Repo / Private Data

這版可放在 Public GitHub repo，因為真實財務數字不寫死在程式碼裡。

- 真實資料只存在瀏覽器 localStorage
- GitHub repo 只會看到空白預設值
- 換裝置 / 換瀏覽器不會自動同步
- 清除瀏覽器網站資料後，私人資料也會被清除

## 更新既有 repo
把本資料夾檔案覆蓋到原本 `finance` 目錄後執行：

git add .
git commit -m "v28 private data version"
git push

## GitHub Pages
1. Repo 改成 Public
2. Settings → Pages
3. Source: Deploy from a branch
4. Branch: main
5. Folder: / (root)
6. Save

## iPhone
Safari 開啟網站 → 分享 → 加入主畫面
