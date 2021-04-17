---
layout: post
title: Jekyll Blog 个人博客搭建(1)
categories: jekyll
date: 2021-04-16
categories: jekyll update
---
 
做个人博客是为了什么，当然是为了学(zhuang)习(bi)了(yong)。看了下别人的学习过程，我也来记录一下github pages + jekyll搭建博客的过程。本文是搭建网站的第一步，建立一个供他人访问的主页。

GitHub Docs 官方教程: 
[https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll)

## Jekyll 介绍

jekyll是一个简单的免费的Blog生成工具，一个生成静态网页的工具，不需要数据库支持，只用 Markdown (或 Textile)、Liquid、HTML & CSS 就可以构建可部署的静态网站。jekyll可以免费部署在Github上，且可以绑定自己的域名。

更多信息查看文档: [http://jekyllrb.com/](http://jekyllrb.com/)

## 搭建过程

个人用的Windows系统
主要过程: 
* 建立 GitHub 库
* 配置 Ruby
* 安装 Jekyll 和 Bundler

### 建立 GitHub 库

登录到GitHub，新建一个Repository，名字一定要是```<user>.github.io```(user为你的GitHub用户名)。

![](ThomasMental.github.io/images/2021-04-16-Jekyll Blog/image1.JPG)

### 配置 Ruby

Windows系统去[https://rubyinstaller.org/](http://rubyinstaller.org)
官网下载RubyInstaller并安装。安装完选择自动运行 

```
  ridk install
```

按提示按Enter就行了。安装完运行指令

```
  ruby -v
```

查看是否安装成功


### 安装 Jekyll 和 Bundler

执行下面的语句安装

```
  gem install jekyll bundler
```
