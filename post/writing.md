---
title: 网站写作功能
mermaid: true
mathjax: true
---

本网站采用 [Jekyll](https://jekyllrb.com) 技术搭建，存放于 [Github](https://github.com/habitism/habitism.github.io)。

## Markdown

本站支持 Markdown 的大部分基本语法，包括但不限于：

- 两个空格 + 回车：同个段落里换行
- 两个回车：进入下一个段落
- *斜体字* 
- **粗体字** 
- ~~删除线~~ 
- <u>下划线</u>
- `高亮`
- [链接](/)
- 脚注[^1]

> 引用

```c
int main() {
	printf("hello world!");
	return 1;
}
```

![picture](img/big.jpg)

|       | mathematics | English | Chinese | Politics |
| ----- | ----------- | ------- | ------- | -------- |
| David | 80          | 80      | 50      | 100      |
| James | 70          | 80      | 90      | 100      |
| Me    | 100         | 90      | 100     | 100      |

## 流程图

流程图由 [Mermaid](https://mermaid.js.org/) 提供支持，样例如下

<div class="mermaid">
graph LR
    A --- B
    B-->C[fa:fa-ban forbidden]
    B-->D(fa:fa-spinner);
</div>

## 数学公式

数学公式由 [MathJax](https://www.mathjax.org/) 提供支持，样例如下

圆的周长 $c$ 和半径 $r$ 的关系:

$$
c=2 \pi r
$$

## 视频嵌入

网站支持 iframe 的视频嵌入，如 B 站视频：

<iframe class="video" src="//player.bilibili.com/player.html?aid=561161150&bvid=BV1Qe4y1B7E7&cid=851166743&page=3" allowfullscreen> </iframe>

## 引用

[^1]: 脚注的引用