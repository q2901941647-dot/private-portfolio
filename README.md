# 唐睿 · 渠道运营作品集 2027

以《鸣潮》3.7 版本「镜锁妄世，心照红尘」为样本做的一份渠道运营案例集，
16 页 A4 横向，涵盖：渠道素材包 / 版本节奏 / 渠道与用户 / UGC 活动运营 / 视觉系统 / 15s 竖屏分镜。

**在线浏览**：部署 GitHub Pages 后，打开仓库的 Pages 地址即可（`index.html` 自动加载）。

## 文件说明

| 文件 | 说明 |
|------|------|
| `index.html` | 作品集正文，单文件（图片已内联，无外部依赖） |
| `portfolio.pdf` | 同内容 PDF，A4 横向 16 页，可直接下载/转发 |
| `.nojekyll` | 让 GitHub Pages 跳过 Jekyll 处理，避免静态资源被忽略 |

## 本地预览

直接双击 `index.html` 即可（不需要起服务器）。

## 部署到 GitHub Pages

### 方式一：网页上传（不用装 Git）

1. 打开 https://github.com/new ，Repository name 填 `portfolio`（或任意名字），选 **Public**，点 Create repository
2. 进入仓库 → **Add file → Upload files** → 把这个目录里的**全部文件**拖进去（含 `.nojekyll`）
3. 点 **Commit changes**
4. 仓库 **Settings → Pages** → Source 选 `Deploy from a branch` → Branch 选 `main` / 目录 `/ (root)` → Save
5. 等 1–2 分钟，访问 `https://<你的用户名>.github.io/<仓库名>/`

### 方式二：命令行

```bash
cd 发布_github
git init
git add -A
git commit -m "portfolio: 渠道运营作品集 2027"
git branch -M main
git remote add origin git@github.com:<用户名>/<仓库名>.git
git push -u origin main
```

推送后在 Settings → Pages 里把 Branch 设为 `main` / `/ (root)`。

> 提示：`.nojekyll` 是隐藏文件，Windows 资源管理器默认不显示，上传时用命令行 `git add -A` 更稳妥。

## 备注

- 页面为固定 A4 版式（297×210mm），浏览器宽度小时会自动等比缩放，建议用桌面端查看
- 游戏内美术版权归库洛游戏所有，本作品集仅用于应聘展示
- 文案、版式、表格与样机图示均为本人产出
