# 董连文 · 个人简历网站

> 董连文（dlw-cloud）的个人简历站点 —— AI 工程实践者 · 燕山大学西里西亚学院 · 电子科学与技术

纯静态站点（HTML / CSS / 原生 JS，无框架），数据驱动渲染，支持深浅色、中英切换、打印导出、证书灯箱。
当前部署目标：**https://dlwdlwdlw.online**（Cloudflare Pages）。

## 目录结构
```
resume-site/
├── index.html       # 主页面（数据驱动容器）
├── favicon.svg      # 网站图标
├── css/style.css    # 全部样式
├── js/main.js       # 全部脚本（resume 数据对象 + 渲染逻辑）
├── images/          # 头像 + 证书图
├── media/intro.mp4  # 旅游视频
└── tank-dlw.html    # DLW 坦克大战
```

## 本地预览
```bash
python -m http.server 8080   # 或 npx serve
# 访问 http://localhost:8080
```

## 修改内容
编辑 `js/main.js` 的 `resume` 对象即可更新展示数据。

## 部署
GitHub 仓库 + Cloudflare Pages。
