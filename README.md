# 灰哥財務諮詢 — 銷售頁

## 🔗 線上網址

| 版本 | 用途 | 網址 |
| :--- | :--- | :--- |
| **兩年・完整版** | **成交用**（諮詢中要報價時） | https://geniusjohn0502.github.io/plan-2028/2year/ |
| **兩年・無報價版** | **給諮詢後的學員參考**（無定價、無 FAQ） | https://geniusjohn0502.github.io/plan-2028/2year-info/ |
| 三年百萬計畫 | 舊版，去留待議 | https://geniusjohn0502.github.io/plan-2028/ |

---

## 📁 檔案對照

```
plan-2028/
├── index.html            三年百萬計畫（舊結構，尚未改版）
├── 2year/index.html      兩年槓桿加速計畫・完整版
├── 2year-info/index.html 兩年槓桿加速計畫・無報價版
└── 見證素材/              學員對話截圖原圖（已壓縮內嵌進 HTML）
```

---

## ⚠️ 改版鐵律

**兩年版有兩個檔案，它們是獨立副本、不會自動同步。**

改 `2year/index.html` 的內容（見證、數字、文案）時，**必須同步改 `2year-info/index.html`**，否則兩版會分岔。

`2year-info` 與 `2year` 的唯一差別：**切掉「價值堆疊＋定價＋滿意保證」與「常見問題」兩個 section**，頁面結束在「誰不適合參加」。改完請確認無報價版沒有殘留：`19,800`／`16,800`／`老學員`／`優惠價`／`總價值`／`滿意保證`／`常見問題`。

---

## 🛠 改版流程

本機資料夾：`~/Documents/John agent/John-Vault/leverage-coaching/銷售頁/`
（實體在 John-Vault 內，但**版控歸這個 repo**；John-Vault 已 gitignore 該資料夾，兩層 git 各管各的）

```bash
# 1. 改 HTML
# 2. 在該資料夾內：
git add -A && git commit -m "說明" && git push
# 3. GitHub Pages 自動重建，約 30 秒～2 分鐘後生效
```

---

## 📝 文案與決策紀錄

純文字版文案、改版理由、定價沿革都在 John-Vault（私有 repo）：

- `leverage-coaching/方案/兩年槓桿加速計畫_銷售頁文案.md`
- `memory/2026-07-26_兩年版銷售頁改版_文欣建議一.md`
- `memory/2026-07-27_銷售頁建議二_並排與對比長條圖.md`
