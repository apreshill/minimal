---
title: diagrammer
output: hugo_document
rmd_hash: 1721073d05a9e885
html_dependencies:
- <script src="htmlwidgets-1.5.1/htmlwidgets.js"></script>
- <script src="viz-0.3/viz.js"></script>
- <link href="DiagrammeR-styles-0.2/styles.css" rel="stylesheet" />
- <script src="grViz-binding-1.0.1/grViz.js"></script>

---



```r
library(DiagrammeR)
grViz("
  digraph {
    layout = twopi
    node [shape = circle]
    A -> {B C D} 
  }")
```

<!--html_preserve--><div id="htmlwidget-88d613c84eae5c93f2e5" style="width:700px;height:415.296px;" class="grViz html-widget"></div>
<script type="application/json" data-for="htmlwidget-88d613c84eae5c93f2e5">{"x":{"diagram":"\n  digraph {\n    layout = twopi\n    node [shape = circle]\n    A -> {B C D} \n  }","config":{"engine":"dot","options":null}},"evals":[],"jsHooks":[]}</script><!--/html_preserve-->
