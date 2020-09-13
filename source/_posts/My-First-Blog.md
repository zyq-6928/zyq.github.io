---
title: My First Blog
date: 2020-05-31 11:44:10
categories: 
- Markdown
tags: Markdown基础
pin: true
---

# Markdown

### 标题

<div align="center" style="color:skyblue">
使用#标记1-6级标题，后加空格。

一级#，二级##，与h1/h2类似</div>
<div style="font-family:'楷体'; color:red; ">直接使用html标签，可设置文字居中、颜色等属性。<u>使用空行来表示换行。</u></b></div>

``` html
<div align="center" style="color:skyblue">
使用#标记1-6级标题，后加空格。

一级#，二级##，与h1/h2类似</div>
<div style="font-family:'楷体'; color:red; ">直接使用html标签，可设置文字居中、颜色等属性。<u>使用空行来表示换行。</u></b></div>
//使用<u></u>来实现下划线
//使用```<div></div>```显示代码区块，并指定语言
```
#### 先使用<kbd>ctrl</kbd>+<kbd>k</kbd>,松开后按<kbd>v</kbd>，即打开实时预览

### 列表

无序列表使用*，使用+/-做列表标记，有序列表使用数字并加上.表示。列表嵌套只需在子列表中选项前加四个空格。

* hi
* How are you?

1. I am fine.
      - And you?
2. I am fine,too.

``` M
* hi
* How are you?

1. I am fine.
      - And you?
2. I am fine,too.

```

### 区块

在段落前与、使用`>`,  后加空格

* one
  
> 1. Q
> 2. K

* two
* three
  
``` M
* one
  
> 1. Q
> 2. K

* two
* three
```

### 字体

* *斜体*
* _好多好多字字字字_
* **粗体**
* \*\* 正常显示*号\*\*
* __字好多好多多多多__
* ***粗斜体***
* ___多字好字好好好好___
  
``` M
* *斜体*
* _好多好多字字字字_
* **粗体**
* \*\* 正常显示*号\*\*
* __字好多好多多多多__
* ***粗斜体***
* ___多字好字好好好好___
```

---

### 分隔线

***
* * *
*****
---
--------

``` M

* ***
* * * *
* *****
* ---
* --------
```

### 删除线

~~love~~

`~~love~~`

### 表格

| 左对齐 | 右对齐 | 居中对齐 |
| :----- | -----: | :------: |
| 1      |      2 |    3     |

``` m
| 左对齐 | 右对齐 | 居中对齐 |
| :----- | -----: | :------: |
| 1      |      2 |    3     |
```

**出现问题:**

1、MD025 - Multiple top level headings in the same document

同一个文档中，只能有一个最高级的标题，默认也只能有一个一级标题

2、MD033 - Inline HTML

文档中不允许使用html语句

3、MD022 - Headings should be surrounded by blank lines

标题的上下行必须都是空格

4.MD036 - Emphasis used instead of a heading

不能用强调代替标题

5.MD040 - Fenced code blocks should have a language specified

单独的代码块（此处是指上下用三个反引号包围的代码块）应该指定代码块的编程语言，这一点有助于解释器对代码进行代码高亮

6.MD032 - Lists should be surrounded by blank lines

列表（有序、无序）前后需要用空行隔开，否则有些解释器不会解释为列表
列表的缩进必须一致，否则会警告

7.MD004 - Unordered list style

整篇文档定义无序列表的格式要一致

8.MD029 - Ordered list item prefix

有序列表的前缀序号格式必须只用1或者从1开始的加1递增数字("one_or_ordered")

9.MD035 - Horizontal rule style

创建水平线时整篇文档要统一(consistent)，要和文档中第一次创建水平线使用的符号一致

[Markdown常见错误速查](https://blog.csdn.net/longtype/article/details/103582331)
