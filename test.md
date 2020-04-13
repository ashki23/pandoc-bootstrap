---
title: "Markdown introduction"
author: "Ashkan Mirzaee"
---

[Markdown](https://daringfireball.net/projects/markdown/) is a text-to-HTML conversion tool for web writers. Markdown allows you to write using an easy-to-read, easy-to-write plain text format, then convert it to structurally valid XHTML (or HTML). A  Markdown document could contain chunks of embedded graphics, source codes and LaTex formula. A basic knowledge about Markdown could help u to create HTML documents such as weblogs or reports easily. This tutorial provides a quick reference to use Markdown.

---

## Headers
<h3 class="title">H3</h3>
#### H4
##### H5
###### H6

```
# Markdown
The following provides quick references to the most commonly used R Markdown syntax.

## Headers
### H3
#### H4
##### H5
###### H6
```

## Emphasis
*Italic* and **Bold**
```
*Italic* and **Bold**
```

~~Scratched Text~~
```
~~Scratched Text~~
```

superscript^2^
```
superscript^2^
```

Markdown doesn't support underline, but we can use <u>HTML Text</u> instead. Also, <b>we</b> can <i>render</i> almost any <span style="color:red;">HTML</span> code that we &nbsp; <kbd>like</kbd>  &nbsp; such as superscript<sup>2</sup>.
```html
Markdown doesn't support underline, but we can use <u>HTML Text</u> instead. Also, <b>we</b> can <i>render</i> almost any <span style="color:red;">HTML</span> code that we &nbsp; <kbd>like</kbd> &nbsp; such as superscript<sup>2</sup>.
```

For manual line or page breaks, we can use following HTML and CSS codes:

- Line breaks:
```html
<br />
```

- Print breaks:
```css
<p style="page-break-after:always;"></p>
```

## Lists
- Item 1
- Item 2
    - Item 2a
    - Item 2b
        - Item 2b-1
        - Item 2b-2

```
- Item 1
- Item 2
    - Item 2a (2 tabs)
    - Item 2b
        - Item 2b-1 (4 tabs)
        - Item 2b-2
```

1. Item 1
2. Item 2
3. Item 3
    - Item 3a
    - Item 3b

```
1. Item 1
2. Item 2
3. Item 3
    - Item 3a
    - Item 3b
```

## Links
http://www.github.com/

```
http://www.github.com/
```

[Github](http://www.github.com/)

```
[Github](http://www.github.com/)
```

## Images
<p align="center">
![Turing's Device](images/turing-doodle.jpg "Alan Turing's 100th Birthday")
</p>

```html
<p align="center">
![Turing's Device](images/turing-doodle.jpg "Alan Turing's 100th Birthday")
</p>
```

Also, we can use HTML to add more styles:

<img src="images/turing-doodle.jpg" alt="Turing's Device" style="width:50%; border:0;">

```html
<img src="images/turing-doodle.jpg" alt="Turing's Device" style="width:50%; border:0;">
```

## Quotes
> Imagination is more important than knowledge.
>
> Albert Einstein

```
> Imagination is more important than knowledge.
>
> Albert Einstein
```

## Hlines
Use three dashes `---` to draw an horizontal line like:

---

```
---
```

## Tables
1st Header|2nd Header|3rd Header
:---|:---:|---: 
col 1 is|left-aligned|1           
col 2 is|center-aligned|2
col 3 is|right-aligned|3

```
1st Header|2nd Header|3rd Header
---|:---:|---: 
col 1 is|left-aligned|1           
col 2 is|center-aligned|2
col 3 is|right-aligned|3
```

## Code blocks
In Markdown, we can simply add plain code blocks to display (not evaluating) by inserting ` ``` `. For example:
```r
norm = function(x) {
  sqrt(x%*%x)
}
norm(1:4)
```
```
`` `r
norm = function(x) {
  sqrt(x%*%x)
}
norm(1:4)
` ``
```

For inline plain codes, for example, we defined the `add` function to compute the sum of two numbers.

```
we defined the `add` function to compute the sum of two numbers.
```

## Mathematical formula
We can use inline LaTex equassion by using sigle `$` before and after the equation for example $y = x + z$. And we can display equations with double `$` such that:

$$\mathbb{N} = \{ a \in \mathbb{Z} : a > 0 \}$$

```latex
$$\mathbb{N} = \{ a \in \mathbb{Z} : a > 0 \}$$
```

$$\forall \; x \in X \quad \exists \; y \leq \epsilon$$

```latex
$$\forall \; x \in X \quad \exists \; y \leq \epsilon$$
```

You may find more extensive references about mathematical formulas at [LaTeX Wikibooks](https://en.wikibooks.org/wiki/LaTeX/Mathematics). 
