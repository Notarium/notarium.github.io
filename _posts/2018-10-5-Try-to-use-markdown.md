---
layout: post
title: Try to use markdown
date: 2018-10-5
---
# markdown入门到放弃

markdown 是一种轻量的标记语言，在各种场合皆有使用，本文自身便是由markdown的一种超集kramdown写成的。我会在这里记录一些基本的操作。

## 一、标题与分段

使用#符号便可以生成标题，几个#符号就是几级标题。
> # 一级标题
> ## 二级标题
> ### 三级标题
> #### 四级标题
> ##### 五级标题
> ###### 六级标题

惊了，6级标题好像是比正文还小了。。。

在markdown里面，单个换行好像是会被忽略的，如果要分段，连续两个换行就可以了

## 二、列表与表格

只要在文本前面加上-就会变成表格啦
>- text1
>- text2
>- text3

这个有点 `<ul>` 的感觉呢

>1. text1
>1. text2
>1. text3

但只要是（数字+.+空格）的组合，就会识别成有序列表，甚至不管你数字写的是什么。。。这就是`<ol>`的效果了把

表格会比较麻烦一些，emmm，见例子

>`|tables    |column |devide |

>|----------|:-------:|-------:|


>|表格|具体|内容|`

以上的内容会被解析成以下格式

>|tables    | column |devide |
>|----------|:-------:|-------:|
>|表格|具体|内容|

简直随心所欲啊。。。。
冒号标记了内容应该向那个方向对齐

## 三、引用，代码引用

引用很简单，在行首输入一个 “>” 然后跟上内容就可以了。
> 引用很简单，在行首输入一个 “>” 然后跟上内容就可以了。
>>引用很简单，在行首输入一个 “>” 然后跟上内容就可以了。
>>>引用很简单，在行首输入一个 “>” 然后跟上内容就可以了。

>(人类的本质就是复读机)


代码的引用，需要用到键盘左上角这个键摁出来的符号，嗯，esc下面这个

> `

就是他
> `<html>`
这样，代码就不会被转义，而且很多渲染器会进行推断，并着色

成段的代码用三个点包在一起，就可以了，很像python那种操作
> *```*

```
#include<stdio.h>
int main (void)
{
    printf("hello world");
    return 0;
}
```

大概就是这种画风吧

## 四、链接，图片，以及其他

图片的语法大概就是`![<picname>](<href>)`

链接的语法大概是`[<hrefname>](<href>)`
差一个感叹号
来个图

![wolf](https://i.pinimg.com/originals/12/7b/32/127b32af4ab99c3dc153a5ae3001ec1e.jpg)

来个链接

[狼](https://i.pinimg.com/originals/12/7b/32/127b32af4ab99c3dc153a5ae3001ec1e.jpg)

嗯。。。

关于字体，用*包起来就可以了

*斜体*

**粗体**

很简单
 
## 五、结语
这篇东西大概就是个笔记，给自己记一下markdown的基本操作，以后可能会继续在nebula上面写一些东西吧，或许不会。。。也许会用英语写，或者用德语写，但肯定主要用中文吧。。。

就写到这里了

时间: 2018-10-5 22:50 CEST
