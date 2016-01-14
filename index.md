---
title       : Interact Deck
subtitle    : Modify some examples
author      : Jennifer Yueh
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax, bootstrap, quiz]            
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
--- &radio

## Question 1

What is $2^0$

1. 0
2. _1_
3. 2

*** .HINT
This is a hint

*** .EXPLANATION
This is an explanation

--- 

## Slide 2


```r
slidifyUI(
  sidebarPanel(
    selectInput('sex', 'Choose Sex', c('Male', 'Female')),
    selectInput('type', 'Choose Type',
      c('multiBarChart', 'multiBarHorizontalChart')
    )
  ),
  
  mainPanel(
    tags$div(id = 'nvd3plot', class='shiny-html-output nvd3 rChart')
  )
)
```

```
## Error in eval(expr, envir, enclos): could not find function "slidifyUI"
```


