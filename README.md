# 產業共生文獻庫

個人論文知識庫：產業共生（Industrial Symbiosis）× Agentic AI。每篇論文整理成固定欄位的結構化筆記，另有跨論文比較表。

- 網站：部署在 GitHub Pages（`main` 分支根目錄）
- 本機預覽：直接用瀏覽器開啟 `index.html`
- 專案規則與「新增一篇論文」的流程：見 [`CLAUDE.md`](CLAUDE.md)

## 新增論文

1. 把 PDF 放進 `_inbox/`（不會被上傳）。
2. 在這個資料夾開啟 Claude Code，輸入：「依 CLAUDE.md 新增 `_inbox/` 裡的這篇論文」。
3. 檢查筆記內容，確認無誤後自己把 `data/papers.js` 裡該篇的 `reviewed` 改成 `true`。

## 結構

```
index.html / paper.html / compare.html   三個頁面（空殼）
assets/     樣式與程式
data/       論文索引、比較表
notes/      每篇論文一個筆記檔
_inbox/     待處理的 PDF（不上傳）
```

筆記為個人改寫整理，不含論文原文；引用請回到原始論文。
