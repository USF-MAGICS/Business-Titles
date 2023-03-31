# Business Titles

Given a business title (with no additional context), can you predict whether the person's level in the company, the job function, subfunction, etc.? Mario Lim would like that!

## Sample Data for Job Title segmentation

* All files starting with ref_ are reference files
* Title_seed_data_2023-03-08...csv is a sample data file

The sample file has 4 columns:

* Title. That's the raw job title we got
* OP_Job_Level__c. The job level we want to assign to the job title. This was brute forced from the ref files
* OP_Job_Function__c. This is the job function we want to assign to the job title. This was brute forced from the ref files
* OP_IT_Job_Sub_function__c. This is the subfunction of the job title. This column indicate a subfunction if the function is IT

We have around 43M rows from this data set that contains mostly IT related job titles. I can look for other data sets with other of job titles.
