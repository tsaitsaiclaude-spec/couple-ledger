# 兩人的帳

靚仔 & 圓仔的共同記帳 App。單一檔案、離線可用，資料存在各自手機上。

## 怎麼上線

1. 把這個資料夾裡的檔案全部上傳到 GitHub 倉庫的根目錄
2. 倉庫 Settings → Pages → Source 選 `Deploy from a branch`，Branch 選 `main` / `(root)`，按 Save
3. 等一兩分鐘，網址會是 https://tsaitsaiclaude-spec.github.io/couple-ledger/
4. 用手機 Safari 打開該網址 → 分享 → 加到主畫面

## 檔案

- `index.html` — App 本體（已內嵌所有程式與樣式）
- `manifest.webmanifest` — 加到主畫面的設定
- `icon-192.png` / `icon-512.png` — App 圖示

## 尚未完成

雲端同步（Supabase）。目前兩支手機各自記帳、資料不互通。
