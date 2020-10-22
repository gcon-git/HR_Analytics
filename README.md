# HR Analytics  
#### Author: G. Conway  

<hr>

## Project Description  

This project seeks to identify features/variables that contribute to employee attrition using the IBM HR Analytics Employee Attrition & Performance data set from Kaggle.com. See **About this repository --> Files Not Included** section below.

## Other Project Goals

* Experiment using flexdashboard(s) as a workflow framework for future projects.  
* Refresh on regression modeling methods.
* Refresh on R/RStudio. 
* Use GitHub Pages to host .html file(s) and show project output

## Project Output Links

* [Dashboard/workflow](https://gconway012.github.io/HR_Analytics/)  
* [Sample screenshots](https://github.com/gconway012/HR_Analytics/blob/master/sample_screenshots.md) 

<hr>

## Helpful References

1. *Using flexdashboard*, https://rmarkdown.rstudio.com/flexdashboard/using.html.

2. *Create Awesome HTML Table with knitr::kable and kableExtra*, by Hao Zhu, https://haozhu233.github.io/kableExtra/awesome_table_in_html.html#getting_started.

3. *Deploying flexdashboard on GitHub Pages*, by Rami Krispin, dated Sep 4, 2020 at https://ramikrispin.github.io/2020/09/deploying-flexdashboard-on-github-pages/. Provided concise steps to follow to enable repository to host an .html file on GitHub Pages.

4. *RMarkdown directing output file into a directory*, NicE's answer, dated Mar 9, 2015 at https://stackoverflow.com/questions/28894515/rmarkdown-directing-output-file-into-a-directory. Provided necessary code used to knit document/file to a different directory.

## Software utilized

* Mac OSx Catalina version 10.15.7
* R (for Mac) version 4.0.2 (2020-06-22) "Taking Off Again"
* RStudio version 1.3.1073

## Software installation

* Download R at:  https://www.r-project.org.
* Download RStudio at:  https://rstudio.com/products/rstudio/download/.

## R packages utilized

* tidyverse version 1.3.0
* DataExplorer version 0.8.1
* knitr version 1.29
* kableExtra version 1.2.1
* pander version 0.6.3
* gmodels version 2.18.1
* car version 3.0-9
* MASS version 7.3-53
* glmnet version 4.0-2
* randomForest version 4.6-14
* plotly version 4.9.2.1
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

## Files not included  

* Data file 
    - The data for this project can be downloaded from:  https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset.  

* Image file
    - The image used in the dashboard was downloaded from:  https://images.techhive.com/images/article/2016/09/data_science_classes-100682563-large.jpg.  

<hr>

## Important notes

* The resulting dashboard (.html file ) is best viewed on a wide screen monitor.  

* Expand or maximize the dashboard for optimal viewing.  

* Small, or reduced, window sizes cause the top tabs/menu items to move to a second line in the header row. This collapses the page contents in a manner that hides various window/section headers, etc.