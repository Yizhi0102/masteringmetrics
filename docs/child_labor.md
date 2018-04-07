
---
output: html_document
editor_options: 
  chunk_output_type: console
---
# Child Labor Laws as an IV

2SLS estimates of the returns to schooling using child labor laws as instruments for years of schooling [@AcemogluAngrist2000].
This replicates Table 6.3 of *Mastering 'Metrics*.


```r
library("tidyverse")
```

Load the `child_labor` data.

```r
data("child_labor", package = "masteringmetrics")
```


## References {-}

-   <http://masteringmetrics.com/wp-content/uploads/2015/02/ReadMe_ChildLaborLaws.txt>
-   <http://masteringmetrics.com/wp-content/uploads/2015/02/AA_regs.do>
