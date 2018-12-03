# SMU_MSDS_6306_CS2


# Prediction Attrition

## Created by The Borgs (Contributors)
- [Nikhil Gupta](mailto:guptan@smu.edu)
- [James Harding](mailto:harding@smu.edu)
- [Max Moro](mailto:mmoro@smu.edu)

# DDS Analytic

DDSAnalytics is an analytics company that specializes in talent management solutions for Fortune 1000 companies.  Talent management is defined as the iterative process of developing and retaining employees.
 

# Objective 

To gain a competitive edge over its competition, DDSAnalytics is planning to leverage data science for talent management.  The executive leadership has identified predicting employee turnover as its first application of data science for talent management  

# Requirement

Before the business green lights the project, they have tasked our data science team to conduct an analysis of existing employee data.  Identify the top three factors that contribute to turnover. 

# Code Book 

## Approach of the Analysis

The data collected contains a dataset with demografic information about the workers of DDSAnalytics Company. We provided an extensive analysi of the correlation between the differet factos to 

1 Identify (at least) the top three factors that contribute to turnover. 

2 Learning about any job role specific trends that may exist in the data set 

## Data Sources

Follow data sources have been used:

- **CaseStudy2-data.xlsx** dataset contains demografic informtion about the workers in the study

## Analysis 

The full analysis has been created using R and Markdown. 

- The Source file is [CaserStudy02_Final.RMD](https://github.com/jth1911/SMU_MSDS_6306_CS2/blob/master/CaseStud02_Final.Rmd)

- The Output file is [CaserStudy02_Final.html](http://htmlpreview.github.io/?https://github.com/jth1911/SMU_MSDS_6306_CS2/blob/master/CaseStud02_Final.html)

- The GitHub Repository is https://github.com/jth1911/SMU_MSDS_6306_CS2 

# Summary of Findings

## Top three factors that contribute to turnover.:

- Factor 1: Money
    - Lower income leads to higher attrition
- Factor 2: Age
    - Younger employees are more flexible (single) and less likely to be tied to a job
- Factor 3: Intrinsic
    - Low job involvement, satisfaction, and overtime leads to higher attrition

## Job role specific trends that may exist in the data set 

- Lab Technician vs. Research Scientist
    - No obvious reason for higher attrition. More root cause analysis needed.
- Human Resources have high attrition
    - Likely correlated to lower job  satisfaction
- Sales Rep have highest attrition
    - Likely correlated to younger age distribution. 


# Opportunities

- Money Related:
    - Recommend skewing compensation towards higher performing employees 
- Age and Tenure related
    - Recommend giving long vesting  period stocks to critical young employees
    - Dig deeper into why employees with Stock level = 3 are leaving (is it competitive?)
- Intrinsic Factors
    - Recommend developing mentoring programs to increase job involvement.
    - Stress and burnout mitigation program for overtime employees



