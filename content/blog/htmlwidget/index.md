---
title: diagrammer
output: hugodown::hugo_document
categories:
- package
rmd_hash: 4f24b6e85e7255ef
html_dependencies:
- <script src="htmlwidgets-1.5.1/htmlwidgets.js"></script>
- <script src="viz-1.8.2/viz.js"></script>
- <link href="DiagrammeR-styles-0.2/styles.css" rel="stylesheet" />
- <script src="grViz-binding-1.0.6.1/grViz.js"></script>

---



```r
library(DiagrammeR)
#> Warning: package 'DiagrammeR' was built under R version 3.6.2
grViz("
  digraph {
    layout = twopi
    node [shape = circle]
    A -> {B C D} 
  }")
```

<!--html_preserve--><div id="htmlwidget-3f38a8b5c2d8243d691f" style="width:700px;height:415.296px;" class="grViz html-widget"></div>
<script type="application/json" data-for="htmlwidget-3f38a8b5c2d8243d691f">{"x":{"diagram":"\n  digraph {\n    layout = twopi\n    node [shape = circle]\n    A -> {B C D} \n  }","config":{"engine":"dot","options":null}},"evals":[],"jsHooks":[]}</script><!--/html_preserve-->
