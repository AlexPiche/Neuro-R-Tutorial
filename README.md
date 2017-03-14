# Neuro-R-Tutorial

All the code for the tutorial will be available on this repository.

# To Do Before the Tutorial

## Download R

https://cran.r-project.org/

## Download R studio

https://www.rstudio.com/products/rstudio/download/

## Opening RStudio for the First Time

On the right hand side, there is the console. It is where we are going to communicate with R by submitting our instructions. 

On the left hand side, you have the Environment and the History in the top panel. The Environment lists all the variables that you currently have in your work space (i.e. that you can call in the console). History registers all the operations you have sent to R. You can browse it to see your previous commands in the console.

## New Project

I encourage creating a new project for the course as File -> New Project... -> New Directory -> Empty Project -> Directory Name -> R_Tutorial and browse to choose the folder where you want the project to be. It will be easier to manage your project and dataset. 

## Rmarkdown

You may export your code and graphs easily to MS word or pdf following these instructions.

File -> New File -> R markdown -> select the output format to Word -> Ok -> Knit

Note that what is written in MS Word is not connected to the console, and vice-versa. You will need to write the command in both places if you want to keep their workspaces the same.

To insert code in your file, click on "Insert" at the top of the top left panel.

## Required Packages

We need to install certain packages for today's tutorial. It can be done this way:

```{r}
install.packages(c("tidyr", "reshape2"))
```

