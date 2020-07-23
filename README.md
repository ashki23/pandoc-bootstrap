# Pandoc-bootstrap template
Bootstrap 4 template for Pandoc - Converts markdown files into Twitter Bootstrap styled HTML.

```
pandoc test.md -o test.html --template template.html --include-in-header header.html --include-before-body navbar.html --include-after-body footer.html --standalone --mathjax --toc --toc-depth 2
```
