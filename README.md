
![giphy](https://github.com/lois4801/Bike.Store.Performance.Analysis--Excel.PowerQuery-To-ExcelVisualization/assets/96842662/289984a8-0a36-494e-a5c1-c5f7dc48f5e7)

•	For more projects to share like this. Please support me by following me in my social media accounts.

Github>>>>>>>https://github.com/lois4801

LinkedIn>>>>> https://www.linkedin.com/in/artemis-jay/).


# Bike Store Performance Analysis
- A store who sells bikes in North America, Europe, and Pacific  needed some help in analysing the raw data they have . The data is comprised of 1026 rows, and 13 attributes.

## The owner wanted to acquire the answers for the following questions.
- How much per region are my buyers for male and female? Where should I focus, and who are my leads?

- Which profession has the highest and lowest average income for my buyers and non buyers?
Who are my hot leads and cold leads?

- What is the average income of married and single customers?
  Should I target more married couples or single couples in our google ads or in marketing campaign?
  
- For our marketing campaign and ads campaign who should I target in facebook, twitter and tiktok ?
  Define the buyers quantity per age group and per region.

- I am interested to know the commute distance trendline of my buyers and non buyers.
  Who buys more? Is it those who travels more and travels less?

  
![b3](https://github.com/lois4801/Bike.Store.Performance.Analysis--Excel.PowerQuery-To-ExcelVisualization/assets/96842662/198d9b96-0725-48cb-b288-63d4842fcdaf)

![b4](https://github.com/lois4801/Bike.Store.Performance.Analysis--Excel.PowerQuery-To-ExcelVisualization/assets/96842662/6c4c94bf-e7fe-414e-ab47-b5b6f1ccabad)

## Data Cleaning
- Removal of 26 duplicate values
  
 ![b5](https://github.com/lois4801/Bike.Store.Performance.Analysis--Excel.PowerQuery-To-ExcelVisualization/assets/96842662/820553bf-7b83-419f-8b7e-31842e744396)

![b6](https://github.com/lois4801/Bike.Store.Performance.Analysis--Excel.PowerQuery-To-ExcelVisualization/assets/96842662/4772cc15-0e6f-4795-ae6c-e8a4e01bebd3)

- There are data uncertainties in between Gender, and Marital Status. 
-	Under Marital Status, change M to Married and S to Single
-	Under Gender, change M to Male and F to Female

![b7](https://github.com/lois4801/Bike.Store.Performance.Analysis--Excel.PowerQuery-To-ExcelVisualization/assets/96842662/fe4812cd-4a82-4013-8382-6bf43104646d)

## Excel Pivot Data Anomalies and Issues Troubleshooting
-	I have noticed that all my columns have blanks. Upon checking it turns out that these are the header columns of my  OCCUPATION AND HOMEOWNER. Thus,  I have to uncheck all blanks , so in turn it wouldn’t affect my pivot tables later.

![b8](https://github.com/lois4801/Bike.Store.Performance.Analysis--Excel.PowerQuery-To-ExcelVisualization/assets/96842662/84963ab8-fa0e-45d5-a551-da525d7c4db2)

-	Checked the age and decided to create an age bracket to easily identify what category they fall into.
- Tried using AI to help me generate the proper formula for it.
"   =IF(AND($L1>=25,$L2<=35),"Adolescent",IF(AND($L2>=36,$L2<=65),"Middle Age",IF(AND($L2>=66,$L2<=89),"Old Age","Unknown Category")))    "

![b9](https://github.com/lois4801/Bike.Store.Performance.Analysis--Excel.PowerQuery-To-ExcelVisualization/assets/96842662/babadb57-8a8b-4fc3-8ba4-afe92cce86a0)


- Encountered a problem while creating my table through the pivot I have made. It might have changed after I did the transformation. Thus, I have to go back and filter it then change that row data to married as well.

![b10](https://github.com/lois4801/Bike.Store.Performance.Analysis--Excel.PowerQuery-To-ExcelVisualization/assets/96842662/e6652016-0c58-4713-a028-4f914d6f8633)

-	I also transformed the values of my data into  whole numbers and placed a currency to avoid the following errors. 

![b11](https://github.com/lois4801/Bike.Store.Performance.Analysis--Excel.PowerQuery-To-ExcelVisualization/assets/96842662/d23baa73-0586-40b4-9216-66d8c700d1f7)

- This is the correct one.
![b12](https://github.com/lois4801/Bike.Store.Performance.Analysis--Excel.PowerQuery-To-ExcelVisualization/assets/96842662/db267187-9ac0-4fef-bbeb-3e367a2ea6f3)

- There is an issue after pivoting under the commute distance.  The 10+ Miles is in the second row instead of last row.

 ![b13](https://github.com/lois4801/Bike.Store.Performance.Analysis--Excel.PowerQuery-To-ExcelVisualization/assets/96842662/ae387e02-384c-4193-bb44-d22c3f746a2d)

![b14](https://github.com/lois4801/Bike.Store.Performance.Analysis--Excel.PowerQuery-To-ExcelVisualization/assets/96842662/684c64d5-aeba-4cb7-b8e3-b0a833d1bcba)


![s10](https://github.com/lois4801/Bike.Store.Performance.Analysis--Excel.PowerQuery-To-ExcelVisualization/assets/96842662/e0909539-ce45-4577-92f9-af9ce7e2cc82)

    
