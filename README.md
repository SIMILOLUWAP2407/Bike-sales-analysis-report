# Bike-sales-analysis-report

## INTRODUCTION 
The purpose of this analysis is to provide targeted answers regarding bike buyers in a certain region who fall into distinct age, income, and educational categories. The assessment's dataset was obtained from PSP Data Analytics/Science course.

## DATA ANALYSIS PROCESS  
The following steps were used in order to analyse this data effectively: 

- Data collection
- Data Cleaning and Formatting
- Data Exploration
- Data Visualization
- Insights and Recommendation 

## DATA COLLECTION 
Joseph Elijah's email served as the source of this information. Two files; the group assessment question and the assessment spreadsheet—were attached to the email. 
Multiple data rows and columns with a variety of data pieces appeared on the assessment document in Microsoft Excel.  

## GIVEN QUESTIONS:
This data analysis was driven by the assessment questions that were provided. 

A. Data Cleaning 
- Remove Duplicates
- Replace M and S in column 2 to Married and Single... And same for M and F using Male and Female in column 3
- Make sure the income column has values with '0' decimal places.
- Group the age into age brackets in a different column with adolescents (0-30), middle age (31-54), and old (55+). Tip: Use the 'IF' function. 

B. Data Analysis/Visualization 

Using PIVOT tables and charts, show the relationship between:
- The average income of each gender and their bike purchase history.
- Distance travelled by commuters and bike purchase .
- Age bracket and bike purchase.
- From analysis in c above, suggest which age bracket should be given less attention by the Bike Manufacturers. 

C. Reporting 
- Create a mouth-watering dashboard with at least three slicers.
- With the slicer, explain the behaviour of European Middle age singles on Bike purchase.
- With the slicer, deduce which academic qualification earns more

## DATA CLEANING AND FORMATTING 

We had to make sure the data was clean and correctly formatted before moving on to exploration and visualisation. 
This is a screen grab of the original data. 

 ![image](https://github.com/user-attachments/assets/5b2b95a1-714f-4bf2-8be0-ecc5d8392223)

- To quickly identify duplicate rows and blanks, we first highlighted and conditionally formatted the entire sheet in order to eliminate duplicates.
- To obtain unique data, we next utilised the Remove Duplicates function in the Data tab to eliminate duplicates. After eliminating duplicates, we discovered that the ID is the main key in the table.
- Using the Find and Replace option on the HOME tab, we changed M and S as well as M and F with Married and Single with Male and Female in the Marital status and Gender column, respectively.
- The Number Format button in the Home tab was used to format the income column to the dollar currency ($) and 0 decimal places.
- Given the large range, we next used the IF function to divide the ages into three primary age groups. Formula used is given as:
 =IF(L2<=30,"Adolescent",IF(L2<=54,"Middle Age",IF(L2>=55,"Old"))). 

How the dataset looked like after cleaning is given the Cleaned Data sheet in the worksheet.


## DATA EXPLORATION 
Pivot tables were utilised in order to examine the prepared data set and provide answers to the previously mentioned enquiries. To fully grasp which age group bike makers should pay less attention to, we also employed charts, namely line charts.


## DATA VISUALIZATION
Mostly bar charts and line charts were used in Microsoft Excel to visualise the data and create the dashboards for this datasheet. 

![image](https://github.com/user-attachments/assets/7585bf6c-5950-48cb-94b9-43ea3411b843)

- The slicer in the dashboard above allows us to infer the behaviour of middle-aged singles in Europe when they buy bikes
- Based on the slicer, it is calculated that, as the following image illustrates, those with a graduate degree make more money, with an average salary of $70,000.  

## CONCLUSION 
By analysing this data, responses  to a few fundamental business enquiries has been gotten. They include: 
- Which academic qualification yields more?
- Which age category should bike makers pay less attention to?
- How do middle-aged singles in Europe behave when buying bikes? 

## SUGGESTIONS
- Middle aged European singles who buy bikes are seen to go fewer miles, despite having purchased roughly 70 bikes. They therefore travel less and are more prone to stay at home. They could be able to work from home and just require bikes to buy nearby home goods
- The Middle aged market should receive less attention from bike manufacturers because the data shows that this demographic typically purchases more. Therefore, marketers should concentrate more on targeting adolescents and older adults. Marketers should concentrate more on targeting adolescents and older adults .
- The highest average salary, $70,000, is earned by those with a graduate degree. Specifically, singles from the Pacific Region with the highest average income should be the focus of greater attention from bike manufacturers.



