# **Application of Machine Learning Algorithms on Student**
- This is a summary of the project, please find the detail report of the project [here](https://github.com/codekeng00/Application_of_Machine_Learning_Algorithms_on_Student_Performance_Analysis/blob/main/Application%20of%20Machine%20Learning%20Algorithms%20on%20Student%20Performance%20Analysis.pdf).
- This repository provides the code for analysis as well, please find it [here](https://github.com/codekeng00/Application_of_Machine_Learning_Algorithms_on_Student_Performance_Analysis/blob/main/project_code.ipynb). 
## **Objective of Study**
This research project aims to:
1. Provide a greater understanding of the factors influencing Mathematics and Portuguese performance among secondary school students in Portugal. 
2. Analyze and compare the variations between the Mathematics and Portuguese influences.
3. Evaluate the prediction of these variables in the forecasting of Mathematics and Portuguese performance using different predictive models. 
4. Identify the most significant predictors and gain a better understanding of these factors.
## **Data Source**
If you are interested to analyze the datasets, you can get the datasets from here:
https://archive.ics.uci.edu/dataset/320/student+performance

## **Datasets**
The datasets we used were collected from two public schools, i.e. Gabriel Pereira and Mousinho da Silveira. The data samples are collected using questionnaire and school reports. In these datasets, we use the predictors such as school, sex, age, information about the students’ study and lifestyle habits, family details, and three grades.

Total of 395 observations and 649 observations were collected for Mathematics and Portuguese courses respectively. There are 33 predictors of in both datasets respectively. Both include school, sex, age, information about the students’ study and lifestyle habits, family details, and three grades

Attribution of data is shown in the table below

|No.|Attributes|Description and (Domain of the Variable)|
|---|---|---|
|1|school|student's school (binary: 'GP' - Gabriel Pereira or ‘MS' - Mousinho da Silveira)|
|2|sex|student's gender (binary: 'F' - female or 'M' - male)|
|3|age|student's age (numeric: from 15 to 22)|
|4|address|student's home address type (binary: 'U' - urban or 'R' - rural)|
|5|famsize|family size (binary: 'LE3' - less or equal to 3 or 'GT3' - greater than 3)|
|6|Pstatus|parent's cohabitation status (binary: 'T' - living together or 'A' - apart)|
|7|Medu|mother's education (numeric: 0 - none, 1 - primary education (4th grade), 2 - 5th to 9th grade, 3 - secondary education or 4 - higher education)|
|8|Fedu|father's education (numeric: 0 - none, 1 - primary education (4th grade), 2 - 5th to 9th grade, 3 - secondary education or 4 - higher education)|
|9|Mjob|mother's job (nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other')|
|10|Fjob|father's job (nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other')|
|11|reason|reason to choose this school (nominal: close to 'home', school 'reputation', 'course' preference or 'other')|
|12|nursery|attended nursery school? (binary: yes or no)|
|13|Internet|Internet access at home? (binary: yes or no)|
|14|guardian|student's guardian (nominal: 'mother', 'father' or 'other')|
|15|traveltime|home to school travel time (numeric: 1 - <15 min., 2 - 15 to 30 min., 3 - 30 min. to 1 hour, or 4 - >1 hour)|
|16|studytime|weekly study time (numeric: 1 - <2 hours, 2 - 2 to 5 hours, 3 - 5 to 10 hours, or 4 - >10 hours)|
|17|failures|number of past class failures (numeric: n if 1<=n<3, else 4)|
|18|schoolsup|extra educational support (binary: yes or no)|
|19|famsup|family educational support (binary: yes or no)|
|20|paid|extra paid classes within the course subject (Math or Portuguese) (binary: yes or no)|
|21|activities|extra-curricular activities (binary: yes or no)|
|22|higher|wants to take higher education (binary: yes or no)|
|23|romantic|with a romantic relationship (binary: yes or no)|
|24|famrel|quality of family relationships (numeric: from 1 - very bad to 5 - excellent)|
|25|freetime|free time after school (numeric: from 1 - very low to 5 - very high)|
|26|goout|going out with friends (numeric: from 1 - very low to 5 - very high)|
|27|Dalc|workday alcohol consumption (numeric: from 1 - very low to 5 - very high)|
|28|Walc|weekend alcohol consumption (numeric: from 1 - very low to 5 - very high)|
|29|health|current health status (numeric: from 1 - very bad to 5 - very good)|
|30|absences|number of school absences (numeric: from 0 to 93)|
|31|G1|first period grade (numeric: from 0 to 20)|
|32|G2|second period grade (numeric: from 0 to 20)|
|33|G3|final grade (numeric: from 0 to 20, output target)|
## **Project Results**
### **Accuracy of model prediction**
- Summary of the Accuracy of all candidate models for Mathematics course

| Approaches          | Accuracy of Predicted value |
| ------------------- | --------------------------- |
| 13-Nearest Neighbor | 88.78%                      |
| Logistic Regression | 77.55%                      |
| Decision Tree       | 70.43%                      |
| Tree Pruning        | 72.17%                      |
| Bagging             | 73.96%                      |

- Summary of the Accuracy of all candidate models for Portuguese course

| Approaches          | Accuracy of Predicted value |
| ------------------- | --------------------------- |
| 5-Nearest Neighbor  | 88.78%                      |
| Logistic Regression | 88.37%                      |
| Decision Tree       | 88.7%                       |
| Tree Pruning        | 88.7%                       |
| Bagging             | 93.75%                      |
### **Significant factors that affect students result**
- This project found out that the role of parents is meaningful determining student performance.
- Student performance has no influence whether or not is a urban or rural student


