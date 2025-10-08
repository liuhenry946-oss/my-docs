# 我的文档项目

这是一个使用 MkDocs 构建的文档项目，提供完整的文档站点解决方案。

## 项目结构

```
my-docs/
├── docs/                    # 存放 Markdown 文档
│   ├── index.md            # 主页
│   ├── about.md            # 关于页面
│   ├── guide.md            # 使用指南
│   └── api.md              # API 参考
├── .github/
│   └── workflows/
│       └── deploy.yml      # 自动化部署工作流配置
├── mkdocs.yml              # MkDocs 配置文件
└── README.md               # 项目说明
```

## 功能特性

- 📝 基于 Markdown 的文档编写
- 🎨 使用 Material for MkDocs 主题
- 🚀 自动部署到 GitHub Pages
- 🔍 内置搜索功能
- 📱 响应式设计，支持移动端
- 🌙 支持深色/浅色主题切换

## 快速开始

### 本地开发

1. 安装 MkDocs 和主题：
```bash
pip install mkdocs
pip install mkdocs-material
```

2. 启动本地服务器：
```bash
mkdocs serve
```

3. 在浏览器中访问 `http://localhost:8000`

### 构建静态站点

```bash
mkdocs build
```

构建后的文件将保存在 `site/` 目录中。

## 部署

项目配置了 GitHub Actions 工作流，当推送到主分支时会自动部署到 GitHub Pages。

## 自定义配置

编辑 `mkdocs.yml` 文件来自定义：

- 站点名称和描述
- 导航菜单
- 主题配置
- 插件设置

## 贡献

欢迎提交 Issue 和 Pull Request 来改进这个项目。

## 许可证

本项目采用 MIT 许可证。详情请查看 [LICENSE](LICENSE) 文件。
