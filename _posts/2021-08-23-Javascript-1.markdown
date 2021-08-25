---
layout: post
title: JS 基础 - Regular Expression 正则表达式
categories: Javascript
date: 2021-08-23
author: Taochen
---

介绍及总结 JS 正则表达式

## 为什么使用正则表达式

使计算机能够根据正则表达式，检查字符串的规则，提取字符串中符合规则的内容。

## 基础语法

### 检查字符

``` javascript

var reg = new RegExp("a","i");
reg = /a/i;

console.log(reg.test("abc"));

/* 
test() 
    检查字符串是否符合正则表达式规则
    符合返回 true 
    反之 false
*/

```

上面两个reg以不同方式创建，代表的都是检查字符串中是否有a。i代表匹配模式，忽略大小写。一种采取构造函数较为灵活，而第二种使用字面量的方式更为简单。

### 或 or

``` javascript

reg = /a|b|c/; 
reg = /[abc]/;
/*
检查是否含有a或b或c
*/

```

如果是一大串字符，采取以下写法

``` javascript

reg = /[a-z]/; 
reg = /[A-Z]/;
/*
检查是否含有a到z所有字母 大小写版本
*/

```

