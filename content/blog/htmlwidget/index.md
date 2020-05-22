---
title: diagrammer
output: hugodown::hugo_document
rmd_hash: 7b7e5d4c7a8ce3a7
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

<!--html_preserve--><div id="htmlwidget-6f10e5e8eea5639b161c" style="width:700px;height:415.296px;" class="grViz html-widget"></div>
<script type="application/json" data-for="htmlwidget-6f10e5e8eea5639b161c">{"x":{"diagram":"\n  digraph {\n    layout = twopi\n    node [shape = circle]\n    A -> {B C D} \n  }","config":{"engine":"dot","options":null}},"evals":[],"jsHooks":[]}</script><!--/html_preserve-->
