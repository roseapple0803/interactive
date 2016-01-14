---
title       : Interact Deck
subtitle    : Modify some examples
author      : Jennifer Yueh
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax, bootstrap, quiz, shiny, interactive]            
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
--- &radio

## Question 1

What is $2^0$

1. 0
2. _1_
3. 2

*** .hint
This is a hint

*** .explanation
This is an explanation

--- &interactive

## Shiny App Demo

<div class="row-fluid">
  <div class="col-sm-4">
    <form class="well">
      <div class="form-group shiny-input-container">
        <label class="control-label" for="sex">Choose Sex</label>
        <div>
          <select id="sex"><option value="Male" selected>Male</option>
<option value="Female">Female</option></select>
          <script type="application/json" data-for="sex" data-nonempty="">{}</script>
        </div>
      </div>
      <div class="form-group shiny-input-container">
        <label class="control-label" for="type">Choose Type</label>
        <div>
          <select id="type"><option value="multiBarChart" selected>multiBarChart</option>
<option value="multiBarHorizontalChart">multiBarHorizontalChart</option></select>
          <script type="application/json" data-for="type" data-nonempty="">{}</script>
        </div>
      </div>
    </form>
  </div>
  <div class="col-sm-8">
    <div id="nvd3plot" class="shiny-html-output nvd3 rChart"></div>
  </div>
</div>



