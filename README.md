# homepage · 三言二鱼首页

[rockdork.cn](https://rockdork.cn) 的首页。**单页静态站**——手写 HTML，零依赖，无构建工具。

- 线上：<https://rockdork.cn>
- 部署：GitHub Pages（本仓 `main` 分支），自定义域名由 `CNAME` 指定

## 有什么

```text
homepage/
├── index.html                   整站就这一个页面（样式内联，中英双语）
├── hero-bg.jpg                  旧版首屏背景图（当前页面未引用，可删）
├── CNAME                        自定义域名 → rockdork.cn
└── 729b6785….txt                域名归属验证文件（🚫 勿删）
```

## 从哪开始

| 要做的事 | 怎么做 |
|---|---|
| 改文案 / 样式 / 排版 | 直接编辑 `index.html`，存盘即生效（**无构建步骤**） |
| 本地预览 | `open index.html`，或 `python3 -m http.server` |
| 发布 | 提交并推送到 `main`，GitHub Pages 自动上线 |

## 相关站点

| 站点 | 说明 |
|---|---|
| [blog.rockdork.cn](https://blog.rockdork.cn) | 博客（Hugo 框架仓 `rockdork/rockdork.github.io`，文章源在私有仓 `rockdork/sanyan-content`） |
| [tutu.rockdork.cn](https://tutu.rockdork.cn) | 图床 |
