# 來源與翻譯說明

## 來源

- 原作者：Sahil Lavingia；其他貢獻者資訊保留於 Git 歷史。
- 原專案：https://github.com/slavingia/skills
- 翻譯基準 commit：`eb9f57fba03ddb0382ed3bfe6654d3d7df128c70`。
- 整理日期：2026-09-27。
- 原 `.claude-plugin/plugin.json` 宣告 `license: MIT`；這個基準版本沒有獨立 LICENSE 檔。本版本保留原宣告，沒有自行補寫作者的法律聲明。
- 這是 AI 協助製作的非官方繁體中文翻譯，未經原作者審定。

## 翻譯範圍

10 個 SKILL.md 的前置描述、角色指示、原則、步驟、例子、引文、清單、表格與輸出要求，以及原 README 全文。

兩個 JSON 的所有欄位均於 PLUGIN-METADATA.md 對照說明；機器欄位與識別值保留原樣。文件內英文產品名、指令、程式碼及網址不翻譯。這是來源專案的翻譯，不是整本書的翻譯。

## 一致用語

| 英文 | 本譯文用語 |
|---|---|
| community / audience | 社群／受眾 |
| manual | 手動 |
| processize / productize | 流程化／產品化 |
| MVP | 最小可行產品 |
| product-market fit | 產品市場契合 |
| bootstrap | 自力更生 |
| runway | 續航力 |
| default alive / default dead | 照目前走勢能存活／會倒閉 |
| build in public | 公開打造 |
| magic piece of paper | 神奇的一張紙 |

## 忠實性與閱讀邊界

翻譯保留原文立場，包括絕對化敘述。這不表示編者確認其普遍正確。文中價格、費率、公司案例與服務名稱為原文內容，未逐項重新查證現況。評論與改進建議集中在 ARCHITECTURE-REVIEW.md，並非原作者文字。

`zh-TW/skills/` 是對照閱讀副本。保留 `name` 等識別欄位，是為了觀察原架構；沒有修改原插件載入位置，也沒有測試把兩組同名 Skills 同時安裝的行為。

## 完整下載的意思

本機透過一般完整 git clone 取得 Git 儲存庫，未使用 shallow depth；包含 Git 歷史與遠端分支。GitHub 副本使用 Fork，保留上游關係。下載範圍不包含 GitHub Issues、PR 討論、Actions 產物或外部網站，這些不是 Git 儲存庫檔案。
