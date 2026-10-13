# Pratyush Kumar: Data Stories

Personal website and blog for ETC5523 Communicating with Data, Assignment 3 (Monash University, Semester 2, 2026).

* **Author:** Pratyush Kumar (student ID 36622680)
* **Live website:** https://etc5523-2026.github.io/etc5523-assignment-3-prat0012-ai/
* **Blog post:** *In 2011, Germany had fewer hospital infections per patient, but more per person*, adapted from my Assignment 2 report on Zacher et al. (2019).

## Intended audience

This blog post is written for curious general readers with no health or statistics background who want to understand why a country with good hospital hygiene can still end up with more hospital infections.

## Generative AI declaration

**Generative AI declaration:** I used Claude (Anthropic) to help plan the structure of the blog post using the unit's Week 1 to 10 material and my Assignment 2 feedback, to suggest and edit wording for the blog post and About page, to write and debug the R code for the figure and table, to write the CSS for the site theme, to crop my profile photo, and to help fix Quarto rendering and Git issues. I checked and revised all generated code and text, and I am responsible for the final content.

## How to build the site

The site is built with [Quarto](https://quarto.org/) and R (packages: ggplot2, dplyr, knitr, kableExtra, tibble, scales).

```bash
quarto render posts/germany-hospital-infections/index.qmd
quarto render
```
