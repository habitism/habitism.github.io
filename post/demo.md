---
permalink: /demo.html
title: 「网站」写作风格展示
mathjax: true
mermaid: true
---

写这篇文章，一方面用于记录我的写作语法，另一方面用于展示网站风格。

该网站支持 Markdown 格式，本文默认你了解 Markdown 语法，这里只展示效果。

## 图片

![picture](img/img.jpeg)

## 视频

<iframe 
class="video" 
src="//player.bilibili.com/player.html?aid=561161150&bvid=BV1Qe4y1B7E7&cid=851166743&page=3" 
allowfullscreen> 
</iframe>

## 代码

C 代码样例如下：

```c
int main() {
	printf("hello world!");
	return 1;
}
```

超长代码样例如下：

```
My father used to say, whatever you do, do it a hundred percent, when you work, work, when you laugh, laugh, when you eat, eat like it is your last meal.
```

## 引用

> 想要和得到，中间还有两个字，那就是要做到，只有做到了才能得到。

## 列表

无序列表如下：

- 数学
- 英语

有序列表如下：

1. 打开冰箱
2. 装入大象

## 表格

简易表格如下：

|       | mathematics | English | Chinese | Politics |
| ----- | ----------- | ------- | ------- | -------- |
| David | 80          | 80      | 50      | 100      |
| James | 70          | 80      | 90      | 100      |
| Me    | 100         | 90      | 100     | 100      |

超长表格如下：

|       | mathematics | English | Chinese | Politics | Japanese | python | basketball | javascript |
| ----- | ----------- | ------- | ------- | -------- | -------- | ------ | ---------- | ---------- |
| David | 80          | 80      | 50      | 100      | 98       | 100    | 99         | 1          |
| James | 70          | 80      | 90      | 100      | 12       | 90     | 88         | 2          |
| Me    | 100         | 90      | 100     | 100      | 120      | 50     | 77         | 3          |

不过一般不使用超长表格，影响阅读体验。

## 段落

- 两个回车：进入下一个段落
- 两个空格 + 回车：同个段落里换行

## 文本

段落中允许不同样式的字体出现，包括：

- *斜体字* ：`*斜体字*`
- **粗体字** ：`**粗体字**`
- ~~删除线~~ ：`~~删除线~~` 
- <u>下划线</u> ：`<u>下划线</u>`

## 数学公式

圆的周长 $c$ 和半径 $r$ 的关系:

$$
c=2 \pi r
$$

## 流程图

<div class="mermaid">
graph LR
    A --- B
    B-->C[fa:fa-ban forbidden]
    B-->D(fa:fa-spinner);
</div>

## 链接

我的知乎 - [「习惯主义」](https://www.zhihu.com/people/habitist)