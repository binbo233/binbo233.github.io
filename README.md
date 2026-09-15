# binbo 的个人网站

这是一个基于 Jekyll 构建、计划通过 GitHub Pages 发布的中文个人网站，用来整理我的个人简介、论文成果、项目经历、兴趣内容与简历。

## 网站内容

- **关于我**：个人经历、网名与头像背后的故事，以及写给自己的话
- **论文**：论文成果与相关研究内容
- **项目**：三得利乌龙茶、中华薪火、爱慕“一缕金”等项目案例
- **简历**：教育经历、实习经历与技能信息
- **兴趣**：AI 实验、游戏体验与古风音乐，分别设有独立的详情页面
- **关于更新**：网站的更新记录

项目详情页与兴趣详情页均使用图文结合的方式呈现，图片、文字和外部链接等素材统一由网站页面引用。

## 项目结构

- `_pages/`：首页、关于我、论文、项目、简历、兴趣及相关页面
- `_publications/`：论文条目
- `_portfolio/`：项目案例条目
- `_sass/`：网站样式与页面布局
- `_data/navigation.yml`：顶部导航栏配置
- `images/`：网站使用的图片、插图与图标
- `files/`：公开文件与可在线查看的资料
- `_config.yml`：网站基本设置、作者信息和社交链接

用于整理内容的本地原始素材目录（如 `实习产出/`、`兴趣.docx` 和 `兴趣图集/`）已加入 `.gitignore`，不会随仓库提交；网站公开版本仅保留经过整理并实际引用的页面内容和素材。

## 本地预览

在项目目录中运行：

```bash
bundle install
bundle exec jekyll serve --livereload
```

然后打开 <http://localhost:4000>。

## 内容维护

- 添加论文：在 `_publications/` 中新增 Markdown 文件
- 添加项目：在 `_portfolio/` 中新增 Markdown 文件
- 修改个人信息：编辑 `_config.yml` 中的 `author` 部分
- 添加或调整栏目：编辑 `_pages/` 和 `_data/navigation.yml`
- 添加图片：将公开图片放入 `images/`，并在页面中引用
- 添加公开文件：将文件放入 `files/`，并通过页面链接提供查看入口

## 声明与许可证

本网站基于 [Academic Pages](https://github.com/academicpages/academicpages.github.io) 模板构建，并保留原项目的声明与 MIT 许可证。许可证全文见仓库中的 [LICENSE](LICENSE) 文件。
