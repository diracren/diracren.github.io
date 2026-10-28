# 个人主页维护说明

正式网址：https://diracren.github.io/

## 日常只修改 index.md

1. 在 GitHub 仓库中打开 `index.md`。
2. 点击铅笔按钮（Edit）。
3. 修改文字，点击 Commit changes 保存。GitHub Pages 会自动更新网站。

不需要修改 HTML，不需要在自己电脑上安装软件。

## Markdown 写法

- `## Research` 是栏目标题。已有栏目标题决定导航链接，建议保留。
- `### 2026 · Paper title` 是论文或条目标题。
- 空一行就是新段落。
- `**文字**` 加粗；`*文字*` 在本网站以期刊颜色显示。
- `[显示文字](https://...)` 添加链接。
- `- 内容` 是列表条目。
- 论文中的粒子符号可直接复制已有符号。

添加论文：复制一整篇论文的标题、作者、期刊三段，粘贴后改文字即可。
添加会议或报告：在 Meetings & Reports 下新增一行 `- **年份 · 会议或报告名称** — 地点、角色或报告链接。`

## 文件用途

- `index.md`：所有正文内容。
- `index.html`：网页外壳，将 Markdown 转成网页，通常无需改动。
- `style.css`：颜色、字号和间距。
- `_config.yml`：GitHub Pages 配置。
- `favicon.svg`：浏览器标签图标。

网站使用 GitHub Pages 自带的 Jekyll 转换 Markdown。不要添加 `.nojekyll` 文件。
直接双击 index.html 无法预览转换结果；使用 GitHub 发布后查看正式网页。
