---
layout: post
title: Jekyll Blog 个人博客搭建(1)
categories: jekyll
date: 2021-04-16
categories: jekyll update
---
 
做个人博客是为了什么，当然是为了学(zhuang)习(bi)了(yong)。看了下别人的学习过程，我也来记录一下github pages + jekyll搭建博客的过程。

GitHub Docs 官方教程: 
[https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll)

## Jekyll 介绍

jekyll是一个简单的免费的Blog生成工具，一个生成静态网页的工具，不需要数据库支持，只用 Markdown (或 Textile)、Liquid、HTML & CSS 就可以构建可部署的静态网站。jekyll可以免费部署在Github上，且可以绑定自己的域名。

更多信息查看文档: [http://jekyllrb.com/](http://jekyllrb.com/)

## 搭建过程

个人用的Windows系统
主要过程: 
* 配置 Ruby
* 安装 Jekyll 和 Bundler

### 配置 Ruby

[https://rubyinstaller.org/](http://rubyinstaller.org)
官网下载RubyInstaller并安装。
安装完自动运行 

<div style="background-color: rgb(50, 50, 50);">
```
  ridk install
```
</div>

按提示按Enter就行了。安装完运行指令

```
  ruby -v
```

安装成功则输出版本号


### 安装 Jekyll 和 Bundler

```
  gem install jekyll bundler
```
