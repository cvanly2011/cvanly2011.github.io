---
layout: post
title: Markdown语法简要规则
categories: Markdown
description: Markdown语法简要规则
keywords: Markdown
---

## 前言

[Markdown](https://zh.wikipedia.org/wiki/Markdown) 是一种轻量级的「标记语言」，它的优点很多，目前也被越来越多的写作爱好者，撰稿者广泛使用。看到这里请不要被「标记」、「语言」所迷惑，Markdown 的语法十分简单。常用的标记符号也不超过十个，这种相对于更为复杂的 HTML 标记语言来说，Markdown 可谓是十分轻量的，学习成本也不需要太多，且一旦熟悉这种语法规则，会有一劳永逸的效果。

## Markdown语法规则

### 标题

![标题](http://ww1.sinaimg.cn/large/6aee7dbbgw1effeaclhiyj20eh09cwez.jpg)

标题是每篇文章都需要也是最常用的格式。在Markdown中，如果一段文字被定义为标题，只要在这段文字前加 # 即可。  
` #一级标题`   
` ##二级标题`   
` ###三级标题`   
以此类推，总共六级标题，建议在井号后加一个空格，这是最标准的 Markdown 语法。

###列表

熟悉 HTML 的同学肯定知道有序列表与无序列表的区别，在 Markdown 下，列表的显示只需要在文字前加上 `-`  或 `*` 即可变为无序列表，有序列表则直接在文字前加`1.` `2.` `3.` 符号要和文字之间加上一个字符的空格。

![列表](http://ww4.sinaimg.cn/large/6aee7dbbgw1effew5aftij20d80bz3yw.jpg)  

###引用

如果你需要引用一小段别处的句子，那么就要用引用的格式。只需要在文本前加入` >`这种尖括号（大于号）即可。  
![列表](http://ww3.sinaimg.cn/large/6aee7dbbgw1effezhonxlj20e009c3yu.jpg)  

###图片与链接

插入链接与插入图片的语法很像，区别在一个 `!`号

图片为：`![](){ImgCap}{/ImgCap}`

链接为：`[]()`

![图片与链接](http://ww2.sinaimg.cn/large/6aee7dbbgw1efffa67voyj20ix0ctq3n.jpg)  

###粗体与斜体

Markdown 的粗体和斜体也非常简单，用两个 `*` 包含一段文本就是粗体的语法，用一个 `*` 包含一段文本就是斜体的语法。

例如：**这里是粗体** *这里是斜体*  

###表格

表格是我觉得 Markdown 比较累人的地方，例子如下：

    | Tables        | Are           | Cool  |
    | ------------- |:-------------:| -----:|   
    | col 3 is      | right-aligned | $1600 |   
    | col 2 is      | centered      |   $12 |    
    | zebra stripes | are neat      |    $1 |   

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|   
| col 3 is      | right-aligned | $1600 |   
| col 2 is      | centered      |   $12 |    
| zebra stripes | are neat      |    $1 |   

###代码框

如果你是个程序猿，需要在文章里优雅的引用代码框，在 Markdown下实现也非常简单，只需要用两个 `` ` 把中间的代码包裹起来。图例：

![代码框](http://ww3.sinaimg.cn/large/6aee7dbbgw1effg1lsa97j20lt0a8dgs.jpg)   
使用 tab 键即可缩进。

###分割线

分割线的语法只需要三个 * 号，例如：

***

##总结
到这里，Markdown 的基本语法在日常的使用中基本就没什么大问题了，只要多加练习，配合好用的工具，写起东西来肯定会行云流水。更多的语法规则，其实 Mou 的 Help 文档栗子很好，当你第一次使用 Mou 时，就会显示该文档。可以用来对用的查找和学习。











