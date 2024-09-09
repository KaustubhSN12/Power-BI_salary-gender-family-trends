# Trends Dashboard

### Dashboard Link : https://app.powerbi.com/groups/me/reports/1583107f-4efb-4266-9bbf-03a643163a1f/ReportSection?experience=power-bi

## Problem Statement

This dashboard helps Analysis  today's rapidly evolving workplace, understanding how gender, family dynamics, and career choices influence financial outcomes is essential. Our task is to uncover key insights from the provided data to reveal patterns in salary distribution, marital status, and family composition across different occupations. By analyzing factors such as gender-based salary differences, the impact of marital status on earnings, and the relationship between age and salary progression, we aim to deliver 20 compelling observations that can guide data-driven decisions and foster a more inclusive and equitable work environment.


### Steps followed 

- Step 1: Load Data into Power BI Desktop
A CSV dataset related to salaries, gender, and family dynamics was imported into Power BI Desktop.
- Step 2: Data Profiling in Power Query Editor
In the Power Query Editor, under the "View" tab, options like column distribution, column quality, and column profile were enabled to review the dataset for data quality.
It was observed that there were no errors or empty values in the dataset, making it ready for analysis.
- Step 3: Handling Null or Irrelevant Values
Certain fields like Children Count or Salary may have null values or outliers. While these were insignificant, they were excluded from specific calculations like averages where applicable.
- Step 4: Selecting Report Theme
A theme was selected under the "View" tab to ensure a consistent visual style throughout the report.
- Step 5: Adding Filters for Occupation and Gender
Slicers were added for fields like Occupation and Gender. This allows users to dynamically filter the dataset and gain insights specific to each occupation or gender.
- Step 6: Adding Visual for Average Children Count
A card visual was added to represent the average number of children for a specific occupation or group of individuals based on the selected filters.
- Step 7: Adding Tables and Charts for Breakdown by Marital Status and Gender
A table was added to the canvas to display detailed information such as First Name, Last Name, Gender, Marital Status, Number of Children, and Occupation.
A donut chart was used to visualize the proportion of salary by gender, indicating salary distribution between males and females.
- Step 8: Bar Chart for Marital Status and Children Count
A bar chart was created to show the count of marital status and their sum of children, segmented by Single and Married individuals. This provides an overview of family dynamics within the dataset.
- Step 9: Creating a Measure for Average Salary by Occupation
A new measure was created using DAX to calculate the average salary for each occupation. This was visualized with a bar chart, showing salary ranges for different occupations.
- Step 10: Line Chart for Average Salary by Age
A line chart was added to the report, representing the average salary by age. This allows for the visualization of salary progression over different age groups.
- Step 11: Adding Text Boxes and Branding
Text boxes were used to add a title, company name, and branding elements to the report. A logo was also inserted to enhance the visual appeal.



  
In our dataset, Some parameters were assigned value 0, representing those parameters are not applicable for some customers.

All these values have been ignored while calculating average rating for each of the parameters mentioned above.

        
Snap of Occupation Drop down list ,

![occupation dropdown list](https://github.com/user-attachments/assets/3a16e592-b3ff-4d77-85ac-a6a41107f870)


        


A card visual was used to represent Average of Children.

![card](https://github.com/user-attachments/assets/f6f3b1d8-6ef3-448b-961b-b4c7166de8a7)


    
 A table visual was used to represent Customers details.
 (Scientist)
 

 
![scientist basic table data](https://github.com/user-attachments/assets/441ff793-ab51-41bd-b649-94cb0043dc52)

    
 A Clustered bar chart visual was used to represent Count of Marital Status with their Sum of Children.
 
 
 ![scientist marital status and sun of children](https://github.com/user-attachments/assets/04f5d4ce-b509-4518-9406-dd34b56d7935)

- Step 12: Publishing the Report
The report was finalized and published to Power BI Service for easy access and collaboration.

 
![publish](https://github.com/user-attachments/assets/6bee6236-4f06-4be1-94ca-7c65bf7dcadf)


# Snapshot of Dashboard (Power BI Service)


![dashboard](https://github.com/user-attachments/assets/5e19c273-02e3-43cf-8bf7-d23104f4b1fd)

 
 # Report Snapshot (Power BI DESKTOP)

 
![report](https://github.com/user-attachments/assets/009fff2b-3210-4bee-98cc-62a6642a181c)

# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

## Key Insights Derived from the Report:
## [1] Average Number of Children for Engineers:

The average number of children for engineers is 2.35.
## [2] Salary Distribution by Gender:

    Average Salary for Females: $6,290
    Average Salary for Males: $5,510

## [3]Marital Status and Children Count:

Among single individuals, there are 33 children in total, whereas married individuals have 21 children.
A larger number of single individuals are represented in the dataset.
Salary Breakdown by Occupation:

    Engineers have an average salary in the range of $1,086 to $3,729.
## [4]Average Salary by Age:

    Salary increases gradually with age, peaking between 35-40 years at an average of $10,000.
