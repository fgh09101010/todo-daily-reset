# todo-daily-reset
👉 [每日必做清單 Demo](https://fgh09101010.github.io/todo-daily-reset/index.html)
這是一個每日重置完成狀態的必做清單（To-Do List）專案，  
使用 GitHub Pages 作為前端頁面，任務資料儲存在 GitHub Repo 中的 `tasks.json`，  
並透過 GitHub Actions 每日自動重置任務完成狀態，  
讓你可以跨裝置使用，每天重新打勾代表完成。

---

## 使用方式

打開以下網址，即可使用每日待辦清單：  
👉 [每日必做清單 Demo](https://fgh09101010.github.io/todo-daily-reset/index.html)

---

## 功能說明

- 顯示待辦任務清單
- 可勾選完成狀態，狀態存在瀏覽器 LocalStorage，隔天自動重置
- 任務資料保存在 `tasks.json`，由 GitHub Actions 每日重置完成欄位
- 支援跨裝置瀏覽與操作（只要瀏覽器能上網即可）

---

## 專案內容

- `index.html`：前端頁面與互動功能  
- `tasks.json`：任務資料  
- `.github/workflows/reset_completed.yml`：每日重置任務完成狀態的 GitHub Actions workflow

---

歡迎 fork、修改或提出 issue！
