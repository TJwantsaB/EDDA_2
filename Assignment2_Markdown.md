---
title: "Assignment 2"
author: "Lukas Unruh, Teije Langelaan, Gidon Quint"
date: "`r format(Sys.Date(), '%d %B, %Y')`"
output: 
  pdf_document:
    latex_engine: xelatex
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
set.seed(333)
library(lme4)
library(Matrix)
options(digits=3)
```

Yoo this is the markdown file. I thought we could all work in the same file,
using git pull and push.