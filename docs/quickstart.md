# 快速开始

本页演示如何把本地文档跑起来并发布。

## 本地预览

```bash
pip install -r requirements.txt
mkdocs serve
```

浏览器打开终端里提示的地址（一般为 `http://127.0.0.1:8000`），保存 Markdown 后会自动刷新。

## 构建静态站点

```bash
mkdocs build
```

生成结果在 `site/` 目录，可交给任意静态文件托管。

## 发布到 GitHub Pages

在项目根目录执行：

```bash
mkdocs gh-deploy
```

将构建产物推送到 `gh-pages` 分支。仓库 **Settings → Pages** 中选择从该分支发布即可。
