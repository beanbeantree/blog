---
title: "{{ replace .TranslationBaseName "-" " " | title }}"
date: {{ .Date }}
categories:
- category
- subcategory
tags:
- tag1
- tag2
keywords:
- tech
#thumbnailImage: //example.com/image.jpg
output:
  blogdown::html_page:
    toc: true  
description: ''
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(collapse = TRUE)
```

