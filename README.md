# OH HAI

i wrongly estimated less than $\frac{1}{10}$ chance that math works in org mode now that it's been added to markdown

more complicated expressions like $\sum_{i=0}^{n} x_{i}$ seem a bit off though.

verbatim is ignored, which is good:

``` tex
$\sum_{i=0}^{n} x_{i}$
```

display works with two dollars on their own lines, but only in markdown

$$
\sum_{i=0}^n x_{i}
$$

and backslashed brackets are not supported:

\[
\sum_{i=0}^n x_{i}
\]

as well as the inline variant with backslashed parens: \( \sum_{i=0}^{n} x_{i}\)


compare with [org-mode](README.org) version of the same.
