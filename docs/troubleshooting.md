# 常见问题

## 本地预览端口被占用

`mkdocs serve` 默认使用 `8000` 端口。若被占用可指定端口：

```bash
mkdocs serve -a 127.0.0.1:8001
```

## 导航里点了页面显示 404

- 检查 `nav` 中的路径是否为相对于 `docs/` 的路径（例如 `guide/page.md` 对应 `docs/guide/page.md`）。
- 文件名大小写是否与磁盘上完全一致。

## `mkdocs gh-deploy` 推送失败

- 确认已配置远程仓库权限（SSH 密钥或 HTTPS 凭据）。
- 确认当前目录是包含 `mkdocs.yml` 的仓库根目录。

## 线上样式与本地不一致

确认 `requirements.txt` 中主题版本与本地一致，并在部署环境中重新安装依赖后再构建。
