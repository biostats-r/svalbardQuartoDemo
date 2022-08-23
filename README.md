# quartoDemo

<!-- badges: start -->

<!-- badges: end -->

The goal of the quartoDemo repo is to demonstrate how to use quarto markdown with R to write reproducible documents.
It is designed to be used with the [Enough Markdown to Write a Thesis biostats](https://biostats-r.github.io/biostats/quarto/index.html) book.
It can also be used with the [R Markdown](https://biostats-r.github.io/biostats/rmarkdown/index.html) is you have problems installing or running quarto.

You can download and start quartoDemo with this code

``` r
#install.packages("usethis") # install usethis package if necessary
usethis::use_course("biostats-r/quaroDemo")
```

This ask you whether you want to download and save the project to your computer's desktop. 
You can agree by typing the correct number when asked. If you want the project saving somewhere else, you can either move the project directory or use the `destdir` argument to `use_course` to specify another location). 
When asked, agree to delete the zip file. 
The project will then open in a new Rstudio session.

Files in this repo:

-   README.md - this file
-   quartoDemo.Rproj - RStudio project file. You can open the project by clicking on this file.
-   svalbard_traits.qmd - the quarto markdown file you will be editing
-   svalbard_traits.Rmd - an R Markdown version of the markdown file.  Use this if you have problems installing or running quarto
-   references.bib - bibtex bibliography file
-   nordic-journal-of-botany.csl - citation style language file for Nordic Journal of Botany
-   plos.csl - citation style language file for PLOS
-   data/PFTC4_Svalbard_2018_Gradient_Traits.csv - the data file
-   .gitignore - a file for Git and GitHub - ignore

Trait data were downloaded from <https://osf.io/smbqh>
