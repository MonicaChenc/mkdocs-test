# Markdown 示例

下面是文档里常用的几种写法，可直接复制改写。

## 标题与段落

一级标题在页面里通常由主题显示为文档标题，正文从二级标题开始更稳妥。

段落之间空一行。行内代码用反引号：`mkdocs.yml`。

## 列表示例

无序列表：

- 第一项
- 第二项

有序列表：

1. 先安装依赖
2. 再执行构建

## 代码块

```python
def greet(name: str) -> str:
    return f"Hello, {name}"
```

## 引用块（标准 Markdown）

> **说明**  
> 普通文档用引用块就能突出提示，不依赖额外配置。

> **注意**  
> 若使用显式 `nav`，请保证路径与 `docs/` 下文件名一致。

## 表格

| 命令 | 作用 |
|------|------|
| `mkdocs serve` | 本地预览 |
| `mkdocs build` | 生成静态文件 |
| `mkdocs gh-deploy` | 部署到 `gh-pages` |

## 链接

- [MkDocs 官方文档](https://www.mkdocs.org/)
- [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/)
