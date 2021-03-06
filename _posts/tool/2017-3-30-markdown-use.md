---
layout: post
title: markdown -  语法与使用
category: 工具
tags: markdown
keywords: 工具,markdown
---

## 语法简单规则
### 标题
标题是用#来表示，分六级标题，建议在#后加一个空格

     # 一级标题

    ## 二级标题

    ### 三级标题

### 列表
熟悉 HTML 的同学肯定知道有序列表与无序列表的区别，在 Markdown 下，列表的显示只需要在文字前加上 - 或 * 即可变为无序列表，有序列表则直接在文字前加1. 2. 3. 符号要和文字之间加上一个字符的空格。

    + 无序列表
        * 1
        * 2
        * 3
    - 有序列表
        1. 1
        2. 2
        3. 3

### 引用
引用只需要在相应的文本前加上>即可  
    >貌似是这样

### 链接

* 行内链接

    - 文字链接　`[描述](链接地址)为文字添加链接`
    - 图片链接　`![描述](链接地址)添加图片`
    - 自动链接　`<http://www.baidu.com/>`

* 引用链接

    图片是我从[视觉中国][1]中找的素材,我想把它存到[Github][2]上。  
    [1]:https://www.vcg.com "vcg"  
    [2]:https://github.com "Github"  


### 粗体与斜体
Markdown 的粗体和斜体也非常简单，用两个 * 包含一段文本就是粗体的语法，用一个 * 包含一段文本就是斜体的语法，用三个***包含一段文本表示加粗斜体，两个~~之间的文本表示删除线。

    **哈哈我是粗体**      *you are itlatic*　***加粗斜体***　~~删除线~~

### 代码块

* 行内代码块

使用``表示行内代码

    `console.log('行内')`

* 加强代码块

```
public function code()
{
    return 'Hello World!';
}
```

### 表格

    | Item       |    Value | Qty  |
    | :‐‐‐‐‐‐‐‐‐ | ‐‐‐‐‐‐‐: | :‐‐: |
    | 短线分隔了表头和表身 |    |      |
    | :在左边表示此列左对齐| :在右边表示此列右对齐 |  两边都有冒号表示此列居中   |
    | Phone      |   12 USD |  12  |
    | Pipe       |    1 USD | 234  |

### 注脚

    使用 Markdown[^1]可以效率的书写文档, 直接转换成 HTML[^2], 你可以使用 Typora[^Le] 编辑器进行书写。

    [^1]:Markdown是一种纯文本标记语言

    [^2]:HyperText Markup Language 超文本标记语言

    [^Le]:免费Markdown编辑软件.

### 目录
在想生成目录的地方输入 [TOC]

### 分割线
分割线只需要三个*

***

### 缩进　　
  * 把输入法由半角改为全角。 两次空格之后就能够有两个汉字的缩进。  
  * 在开头的时候，先输入下面的代码，然后紧跟着输入文本即可。分号也不要掉。
直接写  
    1. 半方大的空白&ensp;或&#8194;  
    2. 全方大的空白&emsp;或&#8195;  
    3. 不断行的空白格&nbsp;或&#160;  


哈哈 真神奇
