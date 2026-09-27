# 插件設定：逐欄翻譯與說明

本頁為設定檔說明。原 JSON 保留不變，機器識別用的 key、名稱、路徑、版本與網址不翻譯。

## `.claude-plugin/marketplace.json`

[查看原始檔](../.claude-plugin/marketplace.json)

| 欄位 | 原值或中文意思 | 結構角色 |
|---|---|---|
| `name` | `minimalist-entrepreneur` | 市集識別名稱 |
| `owner.name` | `Sahil Lavingia` | 市集擁有者 |
| `metadata.description` | 根據 Sahil Lavingia《The Minimalist Entrepreneur》製作的 Claude Code Skills。提供從社群出發，建立有利潤、可持續事業的框架。 | 市集說明 |
| `plugins` | 含一個插件物件的陣列 | 市集列出的插件 |
| `plugins[0].name` | `minimalist-entrepreneur` | 插件名稱 |
| `plugins[0].source` | `./` | 指向此儲存庫根目錄 |
| `plugins[0].description` | 根據 Sahil Lavingia《The Minimalist Entrepreneur》製作的 Claude Code Skills。提供從社群出發，建立有利潤、可持續事業的框架。 | 插件說明 |

## `.claude-plugin/plugin.json`

[查看原始檔](../.claude-plugin/plugin.json)

| 欄位 | 原值或中文意思 | 結構角色 |
|---|---|---|
| `name` | `minimalist-entrepreneur` | 插件識別名稱 |
| `description` | 根據 Sahil Lavingia《The Minimalist Entrepreneur》製作的 Claude Code Skills。提供從社群出發，建立有利潤、可持續事業的框架。 | 插件用途說明 |
| `version` | `1.0.0` | 插件宣告版本 |
| `author.name` | `Sahil Lavingia` | 原作者 |
| `repository` | `https://github.com/slavingia/skills` | 上游來源 |
| `license` | `MIT` | 原檔宣告的授權識別碼 |

此版本的 `plugin.json` 沒有 `skills` 陣列。原 README 表示安裝後會註冊 10 個 Skills；本頁只解釋所見檔案，未實際執行安裝測試。
