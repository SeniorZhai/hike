# 成都周边徒步线路库

一个纯静态网页项目，主要文件是 `page.html`，可直接部署到静态托管平台。

## 项目结构

- `page.html`：主页面（含样式、脚本与数据渲染逻辑）
- `data.md`：线路数据说明

## 本地预览

无需安装依赖，直接启动静态文件服务：

```bash
python3 -m http.server 8080
```

浏览器打开：

```text
http://localhost:8080/page.html
```

## 构建命令

这是静态页面项目，无需构建。

- 构建命令：留空，或使用 `echo "No build required"`
- 启动命令：无

## 帽子云部署建议（静态站点）

- 代码源：本仓库
- 构建命令：`echo "No build required"`（或留空）
- 输出目录：`.`
- 首页文件：`index.html`

## Git 推送

如果你要推送到自己的远程仓库：

```bash
git remote add origin <你的仓库地址>
git branch -M main
git push -u origin main
```
