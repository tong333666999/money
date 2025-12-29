# 部署到 Cloudflare Pages

## 快速连接指南

最简单的方法是直接在 Cloudflare Dashboard 中连接你的 GitHub 仓库。

### 步骤：

1. **登入 Cloudflare Dashboard**
   - 访问 https://dash.cloudflare.com/

2. **导航到 Pages**
   - 左侧菜单 → Workers & Pages → Pages

3. **连接 GitHub**
   - 点 "Create" → "Connect to Git"
   - 授权 GitHub 账户
   - 选择 `tong333666999/money` 仓库

4. **配置部署设置**
   - **Project name**: `money-tracker`
   - **Framework**: `None` (静态网站)
   - **Build output directory**: (留空)
   - **Build command**: (留空)

5. **保存并部署**
   - 点 "Save and Deploy"
   - 等待部署完成

### 完成后

每次推送到 `main` 或 `master` 分支，Cloudflare Pages 就会自动部署新版本。

## 查看部署状态

- Cloudflare Dashboard → Pages → money-tracker → 查看部署历史
- GitHub Actions → 查看代码验证状态
