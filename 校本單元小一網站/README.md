# 校本單元（小一）課文互動遊戲 · GitHub Pages

建議倉庫名稱：`xiaoben-p1-classroom`

## 上傳方式

1. 在 GitHub 建立一個**空的 Public** repository（建議名：`xiaoben-p1-classroom`）。
2. 上傳**本資料夾的全部內容**（即 `README.md` 與 `docs/`），讓它們位於 repo **根目錄**。
3. 前往 **Settings → Pages**  
   - Source：Deploy from a branch  
   - Branch：`main`  
   - Folder：**`/docs`**
4. 儲存後稍等一兩分鐘，網站網址會是：

   https://nhto.github.io/xiaoben-p1-classroom/

## 重要提醒

- 必須讓 `docs/` 位於 repo **根目錄**，**不要**再包一層父資料夾再上傳。  
  （先前古詩詞站因巢狀資料夾導致 Pages 出現 `dir_chdir …/docs` 錯誤。）
- 本套件已包含 `docs/.nojekyll`，避免 GitHub Pages 的 Jekyll 處理破壞靜態 HTML。

## 內容

- `docs/index.html`：入口頁（卡片連本地遊戲；二維碼以 QRCode.js 動態產生本站絕對網址）
- `docs/校本教材課文情景遊戲/`：00–11 課文情景遊戲與使用說明
