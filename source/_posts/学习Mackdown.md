---
title: 学习Mackdown
date: 2016-08-05 17:45:00
tags: Mackdown
categories: Mackdown
---
## 概述
在刚才的导语里提到，Markdown 是一种用来写作的轻量级「标记语言」，它用简洁的语法代替排版，而不像一般我们用的字处理软件 Word 或 Pages 有大量的排版、字体设置。它使我们专心于码字，用「标记」语法，来代替常见的排版格式。例如此文从内容到格式，甚至插图，键盘就可以通通搞定了。目前来看，支持 Markdown 语法的编辑器有很多，包括很多网站（例如简书）也支持了 Markdown 的文字录入。Markdown 从写作到完成，导出格式随心所欲，你可以导出 HTML 格式的文件用来网站发布，也可以十分方便的导出 PDF 格式，这种格式写出的简历更能得到 HR 的好感。甚至可以利用 CloudApp 这种云服务工具直接上传至网页用来分享你的文章，全球最大的轻博客平台 Tumblr，也支持 Mou 这类 Markdown 工具的直接上传。

<!--more-->

## Markdown 官方文档
[创始人 John Gruber 的 Markdown 语法说明](http://daringfireball.net/projects/markdown/syntax)
[Markdown 中文版语法说明](http://www.appinn.com/markdown/#link)

## 使用 Markdown 的优点
- 专注你的文字内容而不是排版样式，安心写作。
- 轻松的导出 HTML、PDF 和本身的 .md 文件。
- 纯文本内容，兼容所有的文本编辑器与字处理软件。
- 随时修改你的文章版本，不必像字处理软件生成若干文件版本导致混乱。
- 可读、直观、学习成本低。

## Markdown 语法的简要规则

### 标题
标题是每篇文章都需要也是最常用的格式，在 Markdown 中，如果一段文字被定义为标题，只要在这段文字前加 # 号即可。

- \# 一级标题
- \## 二级标题
- \### 三级标题

以此类推，总共六级标题，建议在井号后加一个空格，这是最标准的 Markdown 语法。

### 列表
熟悉 HTML 的同学肯定知道有序列表与无序列表的区别，在 Markdown 下，列表的显示只需要在文字前加上 - 或 * 即可变为无序列表，有序列表则直接在文字前加1. 2. 3. 符号要和文字之间加上一个字符的空格。

### 引用
如果你需要引用一小段别处的句子，那么就要用引用的格式。例如这样只需要在文本前加入 > 这种尖括号（大于号）即可
> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.

### 图片与链接
插入链接与插入图片的语法很像，区别在一个 !号

#### 图片

语法：
\![Alt text]\(/path/to/img.jpg)
\![Alt text]\(/path/to/img.jpg "Optional title")

详细叙述如下：
- 一个惊叹号 !
- 接着一个方括号，里面放上图片的替代文字
- 接着一个普通括号，里面放上图片的网址，最后还可以用引号包住并加上 选择性的 'title' 文字。

参考式的图片语法则长得像这样：
\![Alt text]\[id]
\[id]是图片参考的名称，图片参考的定义方式则和连结参考一样：
\[id]: url/to/image  "Optional title attribute"
到目前为止， Markdown 还没有办法指定图片的宽高，如果你需要的话，你可以使用普通的img标签。
eg: ![图片案例](\image\searchicon.png)

#### 链接
链接为：\[]()
eg: [链接案例](http://www.appinn.com/markdown/#link)

### 粗体与斜体
Markdown 的粗体和斜体也非常简单，用两个 \* 包含一段文本就是粗体的语法，用一个 \* 包含一段文本就是斜体的语法。
eg:  **粗体样例**    
       *斜体样例*	

### 表格
表格是我觉得 Markdown 比较累人的地方省略

### 代码框
如果你是个程序猿，需要在文章里优雅的引用代码框，在 Markdown下实现也非常简单，只需要用两个 ` 把中间的代码包裹起来。图例：
<pre><code> 
public class aaa{
	
 }
 </code></pre>

### 分割线
分割线的语法只需要三个 * 号，例如：
***

### 相关推荐
#### 工具
图床工具用来上传图片获取 URL 地址
- [Droplr](http://droplr.com/)
- [Cloudapp](http://www.getcloudapp.com/)
- [ezShare for Mac](https://itunes.apple.com/cn/app/yi-xiang/id672522335?mt=12&uo=4)
- [围脖图床修复计划](http://weibotuchuang.sinaapp.com/)

在线好用的Markdown工具，为印象笔记而生
- [马克飞象，专为印象笔记打造的Markdown编辑器，非常推荐](http://maxiang.info/)

#### 相关文章阅读
- [为什么作家应该用 Markdown 保存自己的文稿](http://jianshu.io/p/qqgjln)
- [Markdown写作浅谈](http://www.yangzhiping.com/tech/r-markdown-knitr.html)
- [Markdown 工具补完](http://www.appinn.com/markdown-tools/)
- [Drafts + Scriptogr.am + Dropbox 打造移动端 Markdown 风格博客](http://jianshu.io/p/63HYZ6)
- [图灵社区，怎样使用Markdown](http://www.ituring.com.cn/article/23)
- [为什么我们要学习Markdown的三个理由](http://news.cnblogs.com/n/139649/)
- [Markdown 语法写作入门指南 by ibuick](http://ibuick.me/?p=4093)


