---
layout: post
title: Markdown 语法汇总(同步更新中)
categories: markdown
date: 2021-04-19
---

本文介绍通用的Markdown语法，平台特有不涉及。

## Headers 标题

使用#代表标题级别，具体语法为: 

``` markdown
  # 一级标题
  ## 二级标题
  ### 三级标题
  #### 四级标题
  ##### 五级标题
```

效果图:

### 三级标题

#### 四级标题

##### 五级标题


## Emphasis 强调

```
  **加粗**
  _斜体_
  _斜**加粗**体_
```

效果图:

**加粗** <br>
_斜体_ <br>
_斜**加粗**体_ <br>

## Strikethrough 删除线

```
  ~~装逼~~学习
```

效果图:

~~装逼~~学习

## Hyperlink 超链接

```
[超链接1](https://thomasmental.github.io/)
[超链接2](https://thomasmental.github.io/, '一个链接')
展示链接: <https://thomasmental.github.io/>
```

效果图:

[超链接1](https://thomasmental.github.io/) <br>
[超链接2](https://thomasmental.github.io/ '一个链接') <br>
<https://thomasmental.github.io/> <br>

## Newline 换行

```
  这一句话<br>分两行
```

效果图:

这一句话<br>分两行

## 分割线

```
  ___
  \_\_\_
```

效果图:
___
\_\_\_

## 代码块

``` 
  ```
    printf("hello world");
  ```

  ``` c
    printf("hello world");
  ```
```

效果图: 
``` c
    printf("hello world");
```
