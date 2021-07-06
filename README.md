# Fast-R: Making R work hard so that you don’t have to

## Instructors
- [Alessandro Filazzola](http://www.filazzola.info) 
- [Sophie Breitbart](https://sophiebreitbart.wordpress.com/)

## General Information

Research in ecology and evolution presents a challenge with diverse and complicated datasets. With the wide-spread adoption of R for data management and analysis, there is huge potential for improving the efficiency of processing data. However, there is a significant learning curve with R that inhibits our ability to learn faster methods. Repetitive tasks in spreadsheets or even in R itself can often be revised to be faster, use less code, and have a simpler output. Copy-paste strategies can lead to errors and can be computation intensive for R relative to other methods. This workshop will explore writing functions, vectorization via the apply family (e.g. apply, lapply, vapply), “for” loops, and parallel computing. We will also touch upon some of the tools in the tidyverse package for large-scale data manipulation. These tools, while on the surface may appear intimidating, can be learned quickly with an exceptional payoff in time-saving efficiency. Using a combination of lecture and hands-on activities, this workshop will familiarize yourself with the tools necessary for improving your relationship with R and saving you time. A basic understanding of R is recommended because it will make the content more relevant and understandable. There is no prior knowledge necessarily for parallel computing or programming. Participants should bring a laptop with R already install using Mac, Linux, or Windows operating system (not a tablet, Chromebook, etc.). 

**Who**: The course is aimed at R beginners or experienced analysts.

**Where**: TBD

**Requirements**: Participants should use a laptop with a Mac, Linux, or Windows operating system (not a tablet, Chromebook, etc.) with administrative privileges. Ideally, two screens would be beneficial to see the video and your workstation at the same time. However, Participation is not necessary and you can simply follow along as I demonstrate. 

**Contact**: Please contact alex.filazzola@outlook.com for more information.

[Live Notepad]


## Schedule (time in UTC)


Time   | Goal
-------|------------
13:00   | Introduction and set-up
13:15 | [Functions](Functions/Functions.html)
13:45 | [Vectorization](Vectorization/vectorization.html)
14:30 | Break
14:45  | [for Loops](forloops/forLoops.html)
15:30  | [Parallelization](Parallelization/parallelization.html)


## Software

[R](http://www.r-project.org/) is a programming language that is especially powerful for data exploration, visualization, and statistical analysis. To interact with R, we use [RStudio](http://www.rstudio.com/).


Windows        |   Mac OS  X   |      Linux
---------------|---------------|---------------
Install R by downloading and running [this .exe](http://cran.r-project.org/bin/windows/base/release.htm) file from [CRAN](http://cran.r-project.org/index.html). Please also install the [RStudio IDE](http://www.rstudio.com/ide/download/desktop).| Install R by downloading and running [this .pkg](http://cran.r-project.org/bin/macosx/R-latest.pkg) file from [CRAN](http://cran.r-project.org/index.html). Please also install the [RStudio IDE](http://www.rstudio.com/ide/download/desktop).|You can download the binary files for your distribution from [CRAN](http://cran.r-project.org/index.html). Please also install the [RStudio IDE](http://www.rstudio.com/ide/download/desktop)


**Packages we will be using:** We recommend you install these ahead of time and ensure they load correctly to reduce troubleshooting in the workshop. 
```{r eval= FALSE}
install.packages(c("here","microbenchmark", "tidyr","dplyr","magrittr","broom","foreach","doParallel"))

```



## Other workshops

If you enjoyed this workshop and were interested in learning more, I have also run workshops on [Logistic Regression](https://github.com/afilazzola/CUELogisticRegression), an [Introduction to Ecological Analyses](https://afilazzola.github.io/UoA.CommunityAnalyses.2018/), and an [Introduction to Functions](https://afilazzola.github.io/Intro2Functions/)

You can find similar style workshops, usually that are longer and go into more detail, with [Software Carpentry](https://software-carpentry.org/). They have teachers available globally and cover all forms of programming beyond R. 

<br>

## Thank You!

<br>

 Center for Urban Environments         |  University of Toronto
:-------------------------------------:|:-------------------------:
![](images/CUElogo.png)                |  ![](images/UoT.png)
 
