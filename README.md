# HR Analytics  
#### Author: G. Conway  

<hr>

## UPDATE(S):

9/29/2020 - Researching a solution to enable a user to view `attritition_analysis.html` file directly in their browser. Until a solution is found & implemented see `sample_screenshots.md` for images of the source code output.

<hr>

## Project Description  

This project seeks to identify features/variables that contribute to employee attrition using the IBM HR Analytics Employee Attrition & Performance data set from Kaggle.com. See **About this repository --> Files Not Included** section below.

## Other Project Goals

* Experiment using flexdashboard(s) as a workflow framework for future projects.  
* Refresh on regression modeling methods.
* Refresh on R/RStudio. 

<hr>

## Software utilized

* Mac OSx Mojave version 10.14.6
* R (for Mac) version 3.6.0 (2019-04-26) "Planting of a Tree"
* RStudio version 1.2.1335

## Software installation

* Download R at:  https://www.r-project.org.
* Download RStudio at:  https://rstudio.com/products/rstudio/download/.

## R packages utilized

* tidyverse version 1.2.1
* DataExplorer version 0.8.0
* knitr version 1.25
* kableExtra version 1.1.0
* pander version 0.6.3
* gmodels version 2.18.1
* car version 3.0-4
* MASS version 7.3-51.4
* glmnet version 2.0-18
* randomForest version 4.6-14
* plotly version 4.9.0
* AUC version 0.3.0

## R package installation

### Packages available through CRAN repository

* You can check to see if a package is available directly from a CRAN repository at:  https://cran.r-project.org/web/packages/available_packages_by_name.html.  

* Use CTRL+F (Windows) or CMD+F (Mac) to quickly search a package name.

* To install the package in R or RStudio use the `install.package("package_name")` command in the console.

### Packages not available through the CRAN repository  

* If a package is not available on the CRAN repository, search for the package by name with your favorite search engine. Many packages are available through individual GitHub pages or R-Forge. 

* If you have to install a package from a site other than a CRAN repository, it's recommended to search for that package's installation instructions. 

<hr>

## About this repository

### Included files

* **attrition_analysis.Rmd**  
    - This file contains the project source code.  
* **attrition_analysis.html**  
    - This file is the knitted output created by the project source code.
    - The source code embedded in the file and can be viewed by clicking the `<\> Source Code` link in the dashboard menu.  

### Files not included  

* Data file 
    - The data for this project can be downloaded from:  https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset.  

* Image file
    - The image used in this project was downloaded from:  https://images.techhive.com/images/article/2016/09/data_science_classes-100682563-large.jpg.  

<hr>

## Important notes

* The resulting dashboard (.html file ) is best viewed on a wide screen monitor.  

* Expand or maximize the dashboard for optimal viewing.  

* Small, or reduced, window sizes cause the top tabs/menu items to move to a second line in the header row. This collapses the page contents in a manner that hides various window/section headers, etc.