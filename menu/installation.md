---
layout: page
title: R Installation and Swirl
---

There will be a few classroom exercises offered to you that you will be able to complete using R. If you are not familiar with R please follow the instructions to install the necessary software and complete the preparatory assignment in R Swirl.

Please let me know if you run into any problems.

## 1 - Install Base-R and RStudio

Use the following links to install the newest versions of Base-R und RStudio.

### Install Base-R
Windows: https://cran.r-project.org/bin/windows/base/R-3.6.2-win.exe

Mac: https://cran.r-project.org/bin/macosx/R-3.6.2.pkg

### Install RStudio
Windows: https://download1.rstudio.org/desktop/windows/RStudio-1.2.5033.exe

Mac: https://download1.rstudio.org/desktop/macos/RStudio-1.2.5033.dmg

## 2 - Complete Swirl tutorial

Swirl is an interactive learning environment for R. Please run the following code to install Swirl in RStudio.

<font style="font-family: 'Lucida Console', Monaco, monospace;">
install.packages("swirl")
library(swirl)
install_course_github("swirldev", "R_Programming_E")
</font>

Finally, run the following line to start the interactive learning programm. It will first ask you your name. Afterwards select 1 in order to start the R Programming course.

<font style="font-family: 'Lucida Console', Monaco, monospace;">
swirl()
</font>
