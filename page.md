---
title: "Markdown introduction"
author: "Ashkan Mirzaee"
description: "An introduction to Markdown"
---

[Markdown](https://daringfireball.net/projects/markdown/) is a text-to-HTML conversion tool for web writers. Markdown allows you to write using an easy-to-read, easy-to-write plain text format, then convert it to structurally valid XHTML (or HTML). A Markdown document could contain chunks of embedded graphics, source codes and LaTeX formula. A basic knowledge about Markdown could help you to create HTML documents such as weblogs or reports easily. This tutorial provides a quick reference to use Markdown.

---

## Headers
### H3
#### H4
##### H5
###### H6

## Emphasis
*Italic* and **Bold**

~~Scratched Text~~

superscript^2^

Markdown doesn't support underline, but we can use <u>HTML Text</u> instead. Also, <b>we</b> can <i>render</i> almost any <span style="color:red;">HTML</span> code that we &nbsp; <kbd>like</kbd>  &nbsp; such as superscript<sup>2</sup>.

## Lists
- Item 1
- Item 2
    - Item 2a
    - Item 2b
        - Item 2b-1
        - Item 2b-2

1. Item 1
2. Item 2
3. Item 3
    - Item 3a
    - Item 3b

## Links
[Github](http://www.github.com/)

## Images
<p align="center">
![logo](https://www.raspberrypi.org/app/uploads/2018/03/RPi-Logo-Reg-SCREEN-199x250.png "Raspberry pi")
</p>


## Quotes
> Imagination is more important than knowledge.
>
> Albert Einstein

## Hlines
Use three dashes `---` to draw an horizontal line like:

---

## Tables
1st Header|2nd Header|3rd Header
:---|:---:|---: 
col 1 is|left-aligned|1           
col 2 is|center-aligned|2
col 3 is|right-aligned|3

## Code blocks
In Markdown, we can simply add plain code blocks to display (not evaluating) by inserting triple back quote i.e. ` ``` `. For example:
```r
norm = function(x) {
  sqrt(x%*%x)
}
norm(1:4)
```

For inline plain codes use single back quote before and after the code, for example we defined `this codes here` in this way.

## Mathematical formula
We can use inline LaTex equassion by using sigle `$` before and after the equation for example $y = x + z$. And we can display equations with double `$` such that:

$$\mathbb{N} = \{ a \in \mathbb{Z} : a > 0 \}$$
