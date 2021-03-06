Programming, analysis and project development with R/RStudio
========================================================
author: Julian 
date: July/August 2015
css: custom.css
font-family: 'Helvetica'
autosize: true

R/RStudio
========================================================

- R: command line based  
  + run script from terminal or console  
- perform analyses in script (*.R)  
- highly flexible  
- integration with Git via projects  

RStudio
========================================================

- wonderful IDE  
- easy to execute scripts  
  + console: `source(filename.script)`  
  + GUI (button)  
  + run sections/lines selectively  
- highlighting for several languages  
- navigate within the script/file via sections  
- use as general text editor


RStudio and project development
========================================================

+ compose and execute  
+ examine plots  
+ help in-browser  
+ view/install packages  
+ command history  
+ view environment variables  
+ much, much more

Coding and project development
========================================================
- write in script, not command line  
- use code sections  
- output code as notebook or HTML  
- use Git/GitHub to track changes  
    + managed by RStudio  
    + commit within IDE
    
Importing data
========================================================
- base R
    + generally used  
    + lots of options to specify structure  
    + can be slow (strings imported as factors)
- `readr`  
    + faster  
    + many of same options as base R  
    + not quite fully developed  
- which to use? judgment call

Plotting data: base R
========================================================
- built-in  
- ugly  
- can be modified (procedural)  
- ability call model objects and plot directly  


Plotting data: `ggplot2`
========================================================
- typically used for majority of plotting  
- procedural  
- several extensions (`ggExtra`, `ggthemes`)  
- plot model objects  
- many other packages use functionality  

Summarizing data
========================================================
- extensive examples in notebooks  
- `summarize()`  
- `str()`  
- `dplyr::glimpse()`  
- mathematical methods  

Grouping data
========================================================
- `plyr`: came first, lots of functionality  
- `dplyr`: next generation, lots of functionality
- likely use both `plyr` and `dplyr`  
- `reshape2`: reshaping data between wide and long

Model creation and classical tests
========================================================
- base R
    + `lm()`  
    + `aov()`  
    + `glm()`  
    + time series methods  
- common classical tests implemented in base R  
- additional common tests: `car` package

Mixed modeling
========================================================
- `lme4`  
- `nlme`  
- other packages available (next)

Additional packages (analysis)
========================================================
- `MASS`: robust regression, transforms, (G)LMM, GLM  
- `gam`: generalized additive models  
- `gamm4`: generalized additive models
- `glmnet`: regularized regression
- `mgcv`  
- `splines`
- use CRAN task views
- examined suggested packages when installing

Additional packages (plotting)
========================================================
- `car`: component + residual plots and related  
- `lattice`: multivariate data  
- `ggivs`, `plotly`: interactive graphics  
- `googleVis`  

Reporting and sharing data
========================================================
- use RStudio to generate reports  
- R Markdown  
- Sweave / `knitr`  
- HTML / R HTML (static web pages)  
- R presentations

Next steps
========================================================

1. Implement analyses using R scripts and R Studio  
2. Create R Markdown file that mirrors analyses and descriptions from Day 2  
3. References  
  + PDF files demonstrate commands  
  + R scripts are executable  


The next hour will focus on how to output the analyses into a more shareable format, and take the various file types and use them to create presentations, static pages and articles/summaries of data and analyses.
