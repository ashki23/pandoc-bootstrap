# Pandoc-bootstrap template
Bootstrap 5 template for Pandoc - Converts markdown files into Twitter Bootstrap styled HTML.

```
pandoc page.md -o page.html --template template.html --include-in-header header.html --include-before-body navbar.html --include-after-body footer.html --standalone --no-highlight --toc --toc-depth 2 --mathjax
```
