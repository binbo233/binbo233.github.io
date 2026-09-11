# binbo 的个人网站

这是一个基于 Jekyll 的中文个人网站，计划通过 GitHub Pages 发布。

网站当前包含以下栏目：

- 论文
- 项目
- 简历
- 兴趣
- 关于更新

Talks、Blog Posts 和 Teaching 栏目目前未启用。

网站内容主要位于：

- `_pages/`：首页、论文、项目、简历、兴趣和关于更新页面
- `_publications/`：论文条目
- `_portfolio/`：项目条目
- `_config.yml`：网站基本设置、作者信息和社交链接
- `_data/navigation.yml`：顶部导航栏
- `images/`：网站图片和图标
- `files/`：可下载文件

## 本地预览

在项目目录中运行：

```bash
bundle exec jekyll serve --livereload
```

然后打开 `http://localhost:4000`。

## 后续修改

- 添加论文：在 `_publications/` 中新增 Markdown 文件
- 添加项目：在 `_portfolio/` 中新增 Markdown 文件
- 修改左侧个人信息：编辑 `_config.yml` 中的 `author` 部分
- 添加或调整栏目：编辑 `_pages/` 和 `_data/navigation.yml`
- 添加图片：将图片放入 `images/`，并在页面中引用

本网站基于 Academic Pages 模板，并保留其 MIT 许可证。
