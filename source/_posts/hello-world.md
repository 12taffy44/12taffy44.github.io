---
title: Hello World
date: 2026-10-01 21:00:00
tags:
---

欢迎来到我的博客，站点已经迁移到 Hexo + [Butterfly](https://butterfly.js.org/) 主题。

## 常用命令

### 新建文章

``` bash
$ hexo new "文章标题"
```

### 本地预览

``` bash
$ hexo server
```

### 生成静态文件

``` bash
$ hexo generate
```

更多用法见 [Hexo 中文文档](https://hexo.io/zh-cn/docs/)。

## 写作方式

在 `source/_posts/` 目录下新建 Markdown 文件即可，文件头部需要 front-matter：

``` markdown
---
title: 文章标题
date: 2026-10-01 21:00:00
tags:
  - 标签
---
```

页面（如关于页）放在 `source/` 下的独立目录中，例如 `source/about/index.md`。

## 部署

推送到 `master` 分支后，GitHub Actions 会自动构建并发布到 GitHub Pages。