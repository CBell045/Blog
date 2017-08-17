---
title: Thesis Thursday 7 - Conclusion
author: Timothy Lin
date: '2017-08-17'
slug: thesis-thursday-7-conclusion
categories: []
tags: ["Thesis Thursday", "R", "Stata"]
subtitle: ''
---

Finally, the last installment of the Thesis Thursday series! Rather than going through what I have done since the previous post (basically more refinements and robustness checks), I decide to some time to reflect on what I have learnt over the past few months. The completed [research paper](/files/mig_cons_paper.pdf) and [accompanying slides](/mig_cons_slides/) can be downloaded from my website.

###On R and Stata

I decided to code the entire project in R this time round and I have to say that I am quite won over by the capabilities of the various packages. 

Features that I like:

- Graphing capabilities. Ggplot2 offers great default graphics, not to mention the numerous other add-ons and mapping tools (plotly, ggally, htmlwidgets, choroplethr, tmap).

- Superior workflow. I can code in R, write a report in R markdown, produce tables in both html and tex, pull together a series of slides using ioslides/slidfy and blog in the same interface. I only moved out of Rstudio when I was writing up my paper (Latex), though bookdown was an attractive alternative.

- Pipe syntax. I used to dislike it but I noticed that I have been using it quite often over the past few months. It does help reduce clutter but requies a certain frame of mind to read the syntax (Think of it as water flowing through a pipe).

- Dplyr. Greatly speeds up the time it takes to do simple data manipulation compared to base R commands (especially egen type commands in Stata).

- Free

Nonetheless, Stata still has certain advantages:

- Help manual. Stata's help files are the best, comprehensive with examples. Unfortunately, some R packages, being user written, are not as helpful. Stackoverflow and google make it much better though.

- Syntax. I still find Stata's syntax more direct and intuitive. A problem with the many user written commands in R is that everyone tries to come up with new names for functions, many of which are not the most intuitive. 

- Reshape. Reshape2 does not allow one to change multiple variables from long to wide. One can use reshape from the DataTable package but I find it a hassle to use another package to do an elementary task.

- Speed. Stata is much faster at reading and processing large datasets on memory.

- Econometric tools. This is a major selling point of Stata and is where it still holds a comparative advantage. Newly developed tools in applied econometrics are first introduced in Stata over R (e.g. ivreg2).


