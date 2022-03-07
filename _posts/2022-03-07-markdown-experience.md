layout: post
title: Test markdown
subtitle: Each post also has a subtitle
categories: markdown
tags: [test]

##Hello World
*斜体*
_斜体_
**粗体**
***斜粗体***
***
---
___
~~hhh~~
<u>下划线</u>
脚注是这样创建的[^mkt]。
[^mkt]:student
* first
* second
* third
+ first
+ second
+ third
- first
- second
- third
1. first
    + first 1
    + first 2
2. second
3. third
> 区块引用
> 还在区块内
还在区块内
> > 嵌套一下
> > > 再嵌套一下
> > 还在第三层
> 区块中使用列表
> 1. 第一项

`printf()`函数
```javascript
console.log("Hello World");
```

[这是一个链接](www.baidu.com)
<https://www.baidu.com>

高级链接
这个链接用 1 作为网址变量 [Google][1]
这和链接用 baidu 作为网址变量 [Baidu][baidu]

[1]: http://www.google.com/
[baidu]: http://www.baidu.com/

![alt 代替文字的文字](http://static.runoob.com/images/runoob-logo.png)
![RUNOOB 图标](http://static.runoob.com/images/runoob-logo.png "RUNOOB")

这个链接用 1 作为网址变量 [RUNOOB][1].
然后在文档的结尾为变量赋值（网址）

[1]: http://static.runoob.com/images/runoob-logo.png
用img标签可以指定图片的高度和宽度
<img src="http://static.runoob.com/images/runoob-logo.png" width="50%">

|表头|表头|
|:----:|----|
|单元格1111111111111111111|单元格|
|单元格|单元格|

不在 Markdown 涵盖范围之内的标签，都可以直接在文档里面用 HTML 撰写。

目前支持的 HTML 元素有:
> `<kbd> <b> <i> <em> <sup> <sub> <br>`等 ，如：
使用 <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd> 重启电脑

\*星号正常显示

公式的语法可以参考KaTex或者MathJax
$y = x+1$
\(y=x+1\)

$$y=x+1$$
\[y=x+1\]

$$
\begin {Bmatrix}
  a & b \\
  c & d
\end {Bmatrix}
$$
$$
\begin{CD}
   A @>a>> B \\
@VbVV @AAcA \\
   C @= D
\end{CD}
$$
