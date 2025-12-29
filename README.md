# 💰 資產管理追蹤器 - 台幣市值統一版

全球資產配置管理工具，用台幣計價統一追蹤：
- 台股
- 美/英股
- 加密貨幣（BTC 等）
- 現金/負債

## 功能

✅ 新增資產並追蹤成本
✅ 實時更新報價（Yahoo Finance）
✅ 自動計算匯率轉換
✅ 視覺化資產配置圖表
✅ 本地儲存（無需後端）

## 快速開始

直接在瀏覽器開啟 `index.html`，數據自動儲存到瀏覽器 LocalStorage。

## 自動部署

推送到 GitHub 後自動部署到 Cloudflare Pages。

1. 設定 GitHub Secrets:
   - `CLOUDFLARE_API_TOKEN`：Cloudflare API Token
   - `CLOUDFLARE_ACCOUNT_ID`：Cloudflare Account ID

2. 每次推送 main/master 分支就自動部署
