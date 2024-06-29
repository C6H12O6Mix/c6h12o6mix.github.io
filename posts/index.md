# 搭建博客Github+Hugo+Lovlet


# 如何用 GitHub Pages + Hugo + Lovlet 搭建个人博客

## 1. 概念，搭建思路和运行环境

### 1.1 什么是 GitHub Pages？

GitHub Pages 是 GitHub 提供的免费托管服务，用于托管静态网站。无论是个人、项目还是组织，都可以利用 GitHub Pages 创建和托管网站。

### 1.2 什么是 Hugo?

Hugo 是一个快速、现代的静态网站生成器，广泛用于创建博客、公司网站、文档网站等。它以速度和灵活性著称，允许用户使用模板和内容文件生成静态 HTML 文件。

### 1.3 什么是 Lovlet?

Hugo 主题 Lovlet 是一个简洁而优雅的主题，专为博客和个人网站设计。它提供了一些关键功能，使用户可以轻松地创建和定制自己的网站。

### 1.4 网站搭建思路

1. 创建 2 个GitHub仓库：
   - 博客源仓库：储存所有 Markdown 源文件（博客内容），和博客中用到的图片等。
   - GitHub Pages 储存由 Hugo 从 Markdown 文件生成的 HTML 文件。
2. 将**博客源仓库**中, 由 Hugo 生成的静态 HTML 文件部署到远端 **GitHub Pages 仓库**中。

> 目的：将博客源文件单独存放到私人仓库里面，避免访客直接从公共的 GitHub Pages 仓库中获取文章源文件



## 2. 创建 GitHub 仓库

### 2.1 创建博客源仓库

1. <img src="../images/img-01.png" width="50%" align="center" />


