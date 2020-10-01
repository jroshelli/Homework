##INFO 550 Project

I am analyzing `NORS` data related to zoonotic enteric outbreaks. 

Before starting the analysis, you will need to install some `R` packages. The `R` command below can be used to install the packages.

```r
install.packages(c("openxlsx","haven","gtools"))
library(openxlsx)
library(haven)
library(gtools)
```

##Data Analysis

To run the analysis, from the project folder you can run

```bash
Rscript -e "rmarkdown::render('HW4.Rmd')"
```

This code will create a file called `HW4.html` output in your directory that contains the results.

