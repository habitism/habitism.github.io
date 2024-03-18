---
permalink: /demo
title: Writing style
mathjax: true
mermaid: true
---

This website supports Markdown format.

## Picture

![picture](img/img.jpeg)

## Video

<iframe 
class="video" 
src="https://embed.ted.com/talks/lang/en/julian_treasure_how_to_speak_so_that_people_want_to_listen"
allowfullscreen>
</iframe>

## Code

```c
int main() {
	printf("hello world!");
	return 1;
}
```

Long code:

```
My father used to say, whatever you do, do it a hundred percent, when you work, work, when you laugh, laugh, when you eat, eat like it is your last meal.
```

## Quote

> the limits of my language mean the limits of my world.

## List

Unordered list:

- Math
- English

Ordered list:

1. Math
2. English

## Table

|       | Math   | English | Chinese | Politics |
| ----- | ------ | ------- | ------- | -------- |
| David | 80     | 80      | 50      | 100      |
| James | 70     | 80      | 90      | 100      |
| Me    | 100    | 90      | 100     | 100      |

Long table:

|       | Math   | English | Chinese | Politics | Japanese | Python | basketball | JS    |
| ----- | ------ | ------- | ------- | -------- | -------- | ------ | ---------- | ----- |
| David | 80     | 80      | 50      | 100      | 98       | 100    | 99         | 1     |
| James | 70     | 80      | 90      | 100      | 12       | 90     | 88         | 2     |
| Me    | 100    | 90      | 100     | 100      | 120      | 50     | 77         | 3     |

## Paragraph

- 2 Enter: Enter the next paragraph
- 2 spaces + Enter: Wrap lines within the same paragraph

## Text

Allow different styles of fonts to appear in a paragraph:

- *italics* ：`*italics*`
- **bold** ：`**bold**`
- ~~delete~~ ：`~~delete~~` 
- <u>underline</u> ：`<u>underline</u>`

## Formula

The relationship between the circumference $c$ and radius $r$ of a circle:

$$
c=2 \pi r
$$

## Flow chart

<div class="mermaid">
graph LR
    A --- B
    B-->C[fa:fa-ban forbidden]
    B-->D(fa:fa-spinner);
</div>

## Link

 - Youtube: [Habitism]({{ site.youtube }})