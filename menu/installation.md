---
layout: page
title: Installation instructions
---

You will need to bring a laptop for this course to work on data analytics practicals in R. Prior to the first session on Friday, Feb 21, please follow the instructions to install all necessary software and complete the preparatory assignment in R Swirl.

If you cannot bring a laptop to the course please let us know asap.

## 1 - Install Base-R and RStudio on your laptops

Use the following links to install the newest versions of Base-R und RStudio.

### Install Base-R
Windows: https://cran.r-project.org/bin/windows/base/R-3.6.2-win.exe
Mac: https://cran.r-project.org/bin/macosx/R-3.6.2.pkg

### Install RStudio
Windows: https://download1.rstudio.org/desktop/windows/RStudio-1.2.5033.exe
Mac: https://download1.rstudio.org/desktop/macos/RStudio-1.2.5033.dmg

## 2 - Install additional software

In order for some R packages to work please additionally install RTools (if you use Windows) und gfortran und clang-7.0.0 (if you use Mac). Use the following links to download the respective installers and run them.

RTools for Windows: https://cran.r-project.org/bin/windows/Rtools/Rtools35.exe
gfortran for Mac: https://cran.r-project.org/bin/macosx/tools/gfortran-6.1.pkg
clang-7.0.0 for Mac: https://cran.r-project.org/bin/macosx/tools/clang-7.0.0.pkg

## 3 - Install necessary packages

For this course we will rely on various R packages that need to be installed. To do this run the following code within your R Console within R Studio.

source("https://raw.githubusercontent.com/cdsbasel/dataanalytics/master/installpackages.R")

Important: to avoid problems during the installation of packages, please enter *n*, when you are asked to install a package from source.

If you do not know how to run this code in R please let us know asap.

## 4 - Complete Swirl tutorial

Swirl is an interactive learning environment for R. Please run the following code to install Swirl in your R.

<font style="font-family: 'Lucida Console', Monaco, monospace;">
install.packages("swirl")
library(swirl)
install_course_github("swirldev", "R_Programming_E")
</font>

Finally, run the following line to start the interactive learning programm. It will first ask you your name. Afterwards select 1 in order to start the R Programming E course. Within this course complete <b>sections 1, 4, 6, 7, and 9</b>.

<font style="font-family: 'Lucida Console', Monaco, monospace;">
swirl()
</font>
