# Case-Study-02
Using Data Analysis to identify factors that lead to attrition at a company. 

This is a class project by Jeremy Dawkins from Southern Methodist Univeristy in Dallas, TX Doing Data Science Course.


<!-- Table of Contents -->
<details>
  <summary>Table of Contents</summary>
  <ol>
  <li><a href="#Description-about-this-project">Description About This Project</a></li>
   <li><a href="#Built-with">Built With</a></li>
   <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    </ol>
</details>

<!-- Description About This Project -->
## Description About This Project

This project is over identifying employee attrition using data science. The company wants to use data science to identify factors that lead to attrition at their firm.
The firm wants to identify the top three factors that contribute to this turnover (that is backed by evidence provided by analysis). The firm is also interested in learning about any job
role specific trends that may exist within their data. Any other observations or trends that is found during this project will be analyzed and shown here. 
Models will be built in this project as well to predict attrition. 

Included in this repository you will find the data sets that are used "CaseStudy2-data.csv." This project and analysis will be conducted in the R language. Various questions are answered in this project which you can find in the R-Markdown file.

A Powerpoint presentation is also given in this repository that was presented. 


<!-- Built With -->
## Built With
- Rstudio
- Excel

<!-- Getting Started -->
## Getting Started
### Prerequisites
You will need installion of various packages like the dplyr package and you can install them into your program for example:
* Dplyr Package
  ```sh
  install.packages("dplyr")
  ```
You will then need to load the package after installing for example:
* Dplyr Package
  ```sh
  library(dplyr)
  ```
Packages Included In This Project is:
- library(dplyr)  #Allows us to pipe data frames to wrangle data we want to analyze
- library(ggplot2) #Allows us to connect data frames with graphs
- library(ggpubr) #Allows us to arrange any plots on 1 chart to display
- library(hrbrthemes) #Allows us to use the theme function when graphing
- library(GGally)    #Allows us to use our correlation matrix
- library(Hmisc)    #Allow us to find the correlation between variables with pvalues included
- library(olsrr)   #To do a variable/ parameter selection of the predictors
- library(caret)   #Use to for the K-fold cross validation of our model
- library(car)    #To look at the added variable plots of the regression model
- library(e1071) #use of the classification model knn and knn.cv
- library(class) #Use of the cross validations techniques
- library(Metrics) #Use for the Rmse() function
- library(leaps) #use for best predictors variables for salary

<!-- Usage -->
## Usage
Many of these packages were used to construct data analysis and EDA on these data sets. 
For example we were able to develop a linear regression model to look at attrition as well as classify if an employee would leave the company using classification. We were also able to look at employees Salaries and what are the major factors of their earnings. 

Plots similar to these were used to examine various departments and their average survey scores. 
![image](https://user-images.githubusercontent.com/89367924/143969046-d7023f95-d001-48c4-bd70-d57de402a41a.png)

This was use to see visually how former employees felt about their specific Job and display a ptoential factor on why they chose to leave. 
![image](https://user-images.githubusercontent.com/89367924/143969137-f4516af7-ccd8-4715-b3af-c8d1458008b9.png)

<!-- LICENSE -->
## License
Distributed under the MIT License. See "License.txt" for more information.

https://github.com/jdawk123/Case-Study-02/blob/main/LICENSE

<!-- CONTACT -->
## Contact

Jeremy Dawkins - [@linkedIn](https://www.linkedin.com/in/jeremydawkins/)
My Email - [@email](jeremydawkins80@gmail.com)
Project Youtube Link: - [@youtube](https://youtu.be/lQ4SXAdsU14)



## Thanks, I hope you enjoy!

<p alight="right">(<a href="#top">back to top</a>)</p>
