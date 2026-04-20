# 项目结构说明

示例仓库中与文档相关的文件布局如下。

```
mkdocs-test/
├── mkdocs.yml          # 站点配置（主题、导航、插件等）
├── requirements.txt    # Python 依赖（MkDocs、主题等）
├── README.md           # 仓库说明（可选）
└── docs/               # 文档源目录
    ├── index.md        # 站点首页
    ├── quickstart.md
    ├── markdown-examples.md
    ├── project-structure.md
    └── troubleshooting.md
```

## `mkdocs.yml` 里常见项

| 配置项 | 作用 |
|--------|------|
| `site_name` | 站点标题 |
| `site_url` | 正式访问地址，影响站内绝对链接生成 |
| `theme` | 主题及主题选项 |
| `nav` | 可选。不写时 MkDocs 会根据 `docs/` 下的 Markdown 自动生成导航 |

## 新增页面

在 `docs/` 下新建 `.md` 文件即可；未配置 `nav` 时，保存后执行 `mkdocs serve` 会自动出现在侧栏。
