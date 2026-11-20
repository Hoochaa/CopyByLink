# CopyByLink
You can copy a set of words by using a link. For example, on instagram, people can't copy a string. You can use this link to let people copy what you want to share.

# 一鍵複製連結

IG 沒辦法讓別人複製文字，這個小網站可以把文字變成「複製按鈕」的連結。

## 使用方式
1. 打開網站（分享模式），輸入要讓別人複製的文字，可加多段。
2. 按「產生分享連結」→「複製連結」。
3. 把連結放到 IG 個人簡介、限動連結貼紙或私訊。
4. 別人點開會看到按鈕，按一下就複製好了。

文字是編碼後放在網址 `#` 後面，不會傳到任何伺服器，也不需要資料庫。

## 架到 GitHub Pages
1. 在 GitHub 建一個新的 repository（例如 `copy`），設為 Public。
2. 上傳 `index.html`（和這份 README）。
3. 到 **Settings → Pages**，Source 選 **Deploy from a branch**，Branch 選 `main`、資料夾 `/ (root)`，按 Save。
4. 等 1～2 分鐘，網址會是 `https://你的帳號.github.io/copy/`。

## 小提醒
- 內容越長連結越長，超過約 2000 字元時某些 App 可能截斷，可搭配短網址服務。
- 任何拿到連結的人都看得到內容，請勿放密碼等敏感資料。
