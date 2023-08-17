---
title: "Statistical Methods for Quatitative Data Analysis"
author: "Martin Nyamu"
date: "2023-08-18"
site: bookdown::bookdown_site
documentclass: book
bibliography: [book.bib, packages.bib]
url: your book url like https://bookdown.org/nyamu/bookdown
# cover-image: path to the social sharing image like images/cover.jpg
description: |
  This is book is a manual to guide in choosing the most appropriate statistical methods when analyzing quantitative data. Moreover, the book will provide you with knowledge and a good understanding of different types of statistical tests based on the type of data and design of the study.  
  
biblio-style: apalike
csl: chicago-fullnote-bibliography.csl
---

# \# Preface {.unnumbered}

\`\`\`{r fig.align='center', echo=FALSE, out.width="60%"}

knitr::include_graphics('img/wrangle-r.png')

\`\`\`

\## Structure of the book {-}

\## Software information {-}

The R session information when compiling this book is shown below:

\`\`\`{r session}

sessionInfo()

\`\`\`

We do not add prompts (\`\>\` and \`+\`) to R source code in this book, and we comment out the text output with two hashes \`##\` by default, as you can see from the R session information above. This is for your convenience when you want to copy and run the code (the text output will be ignored since it is commented out). Package names are in bold text (e.g., \*\*rmarkdown\*\*), and function names are followed by parentheses (e.g., \`bookdown::render_book()\`). The double-colon operator \`::\` means accessing an object from a package.


```r
bookdown::render_book()
```

## Preview book

As you work, you may start a local server to live preview this HTML book. This preview will update as you edit the book when you save individual .Rmd files. You can start the server in a work session by using the RStudio add-in "Preview book", or from the R console:


```r
bookdown::serve_book()
```


