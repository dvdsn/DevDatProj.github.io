---
title: "Course Project Developing Data Products"
author: "Doug Davidson"
date: "June 26, 2018"
output: ioslides_presentation
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = FALSE)
library(plotly)
```

## Slide with Plot (26.06.18)

```{r plot_hp}
plot_ly(mtcars, 
        x = ~wt, 
        y = ~mpg, 
        type = "scatter", 
        mode = "markers",
        color = ~hp)
```

