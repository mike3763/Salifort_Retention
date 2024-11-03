# Salifort_Retention.
### Project Overview
#### This is the Capstone Project completed in Course 7 of the Google Advanced Data Analytics Certificate. This project is similar in nature to my previous project, Waze Predictive Model Project, in that predictive models are built. 
#### The goal of this project is to determine what factors contribute to employees leaving Salifort Motors. The project will cover the full data analysis life cycle (EDA, visualizations, model buidling, and deriving insights from the data). This project will build only random forest models. Two random forest models will be built, one *without* an engineered field, and one *with* an engineered field. The results of these 2 models will then be compared.  

### Business Understanding 
#### Salifort Motors is a large consulting firm, and executive leadership seeks insight into what factors contribute to employees leaving the organization. As may be obvious, having a grasp on this information will ensure the long-term growth and continuance of the company.

### Data Understanding 
The dataset contains 14,999 rows and 10 variables which contain the results of an employee satisfaction survey conducted by the company. Many thanks and acknowledgement to Faisal Qureshi, who provided the data to the Certificate course. Please visit https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-job-prediction?select=HR_comma_sep.csv for more information.

### Jupyter Notebook Workflow.
### This is an outline of the steps completed in the project notebook.
Step | Sub-Step | Task |
|---|---|---|
| 1 | | Imports and Data Loading |
| 2 | | Data Exploration (Initial EDA and Data Cleaning) |
| | 2a | Gather Basic Information |
| | 2b | Data Cleaning - Missing Values, Rename Columns, Encode Variables |
| | 2c | Data Exploration (Continue EDA) |
| 3 | | Data visualizations |
| 4 | | Model Building |
| | 4a | Random Forest - Round 1 |
| | 4b | Feature Engineering |
| 5 | | Random Forest - Round 2 |
| 6 | | Results and Evaluation |

### Modeling and Evaluation 
#### Two random forest models were constructed, and the model *without* the engineered data value performed slightly better on the test data. This was a bit suprising, as the Certificate model *with* the engineered field did better. Of course, I had to alter the code to avoid run-time errors in Anaconda (I needed to use Anaconda to reproduce the projects on my local machine, as of course Coursera is a paid platform). These code alterations, and using different environments are likely the sources of the diescrepancy.

### Conclusion
#### It was determined from this project that the employees are overworked and under rewarded. There were some employees who worked over 275 hours per month, and on 7-8 projects per month. The visualizations illustrated the correlation between excessivve hours worked and high number of projects assigned, and retenton rate. 
#### It was recommended that the number of projects be capped, and that other initiatives be implemented to better reward employees. And there were suggestions of further analysis, which included advising a K-means model be attempted.

