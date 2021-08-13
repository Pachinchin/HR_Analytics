# HR_Analytics

## Problem statement 
Your client is a large MNC and they have 9 broad verticals across the organisation. One of the problem your client is facing is around identifying the right people for promotion (only for manager position and below) and prepare them in time. Currently the process, they are following is:

They first identify a set of employees based on recommendations/ past performance
Selected employees go through the separate training and evaluation program for each vertical. These programs are based on the required skill of each vertical
At the end of the program, based on various factors such as training performance, KPI completion (only employees with KPIs completed greater than 60% are considered) etc., employee gets promotion
For above mentioned process, the final promotions are only announced after the evaluation and this leads to delay in transition to their new roles. Hence, company needs your help in identifying the eligible candidates at a particular checkpoint so that they can expedite the entire promotion cycle. 

![Imgur Image](https://s3-ap-south-1.amazonaws.com/av-blog-media/wp-content/uploads/2018/09/wns_hack_im_1.jpg)



Dataset Description


employee_id	            :Unique ID for employee\
department	             :Department of employee\
region	                 :Region of employment (unordered)\
education	              :Education Level\
gender	                 :Gender of Employee\
recruitment_channel	    :Channel of recruitment for employee\
no_of_trainings	        :no of other trainings completed in previous year on soft skills, technical skills etc.\
age	                    :Age of Employee\≤\
previous_year_rating   	:Employee Rating for the previous year\
length_of_service	      :Length of service in years\
KPIs_met >80%	          :if Percent of KPIs(Key performance Indicators) >80% then 1 else 0\
awards_won?	            :if awards won during previous year then 1 else 0\
avg_training_score	     :Average score in current training evaluations\
is_promoted	(Target)    :Recommended for promotion
 
### Steps to be Applied 
1. Import Packages and Datasets.
2. Performed EDA (Exploratory Data Analysis) - to understanding the Datasets 
3. Explore Train and Test Data and get to know what each Column / Feature denotes.
4. Check for Imbalance of Target Column in Datasets.
5. Visualize Count Plots & Remove Unique Values to infer from Datasets.
6. Check Duplicate Rows from Train Data if present.
7. Fill/Impute Missing Values Continuous - Mean/Median/Any Specific Value & Categorical - Others/ForwardFill/BackFill.
8. Feature Engineering- creat new bins for age 
Feature Creation - Creation of New Feature from the Existing Features.
9. Split Train Data into Predictors(Independent) & Target(Dependent).
10. Data Encoding - Label Encoding, OneHot Encoding and Data Scaling - MinMaxScaler, StandardScaler, RobustScaler options
11. Create Baseline ML Model for Binary Classification Problem.
12. Improve ML Model with Voting Classifier with MODEL Evaluation METRIC - "F1" and Predict Target "is_promoted".
