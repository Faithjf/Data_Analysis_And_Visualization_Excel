# Data_Analysis_And_Visualization_Excel
This Project is for the sake of practice and learning. I cleaned, analyzed and created visualization reports using Microsoft Excel.
# EXCEL_DATA_CLEANING_AND_VISUALIZATION
### INTRODUCTION:
This project uncovers trends in the purchase of bikes, that is, getting a handy understanding of bike purchases. Note, this is just for exercise and practice. This project was inspired by Alex The Analyst, from his immeasurable lessons on youtube and learning resource on linkedin.
The dataset has 13 features and 1027 observations (rows).

## Business task:
Present the segment that purchased bikes more and recommend how to get more sales from the dataset provided.
### Process:
In this project, I cleaned, aggregated, analyzed and visualized data using Microsoft Excel. 
[Dataset](https://github.com/AlexTheAnalyst/Excel-Tutorial/blob/main/Excel%20Project%20Dataset.xlsx)
## Data_cleaning_highlights:
-	First, I employ the use of “remove duplicates”, this lead to the removal of 26 duplicate observations, leaving 1000 unique observations.
-	I did a column check for duplicates using conditioner formatting on the ID column, since it holds unique key information about each client. No duplicate ID was found.
-	Next, I checked for data consistency format across each column, here I replaced abbreviated entries with a more formal label, e.g. “f” for “Female”. And each column was properly fixed to meet the project needs.
-	I trimmed the columns that contain text strings to avoid errors during data aggregation. 
-	For the purpose of visualization, I inserted a new column “age bracket” to aggregate the ages into intervals in the observation, (26-36, 37-47, etc).
## Pivot_table_summary_report:
1. Purchase analysis by Gender: this report creates reviews on number, averages, income of bike purchases by gender. It was seen that 239 females and 242 males purchased bikes, making a total of 481 persons that purchased bikes, with their average income of $55,774.06 and $60123.97 respectively. 
2. Bike purchase by Age bracket: It was recorded that age group between 25 to 47years had the highest purchases of bike while 48years and above purchased few. This inferred that younger people tends to buy more bikes. 
3. Bike purchase by region: I view the number of purchases by region to determine which region had the highest. It was seen that North America had the highest purchase of 220, followed by Europe 148 purchases and lastly Pacific which had 113 purchases.
4. Bike purchase by Marital Status: Next, I viewed the number of purchases by marital status, I noticed just I slight difference between married and single people that bought bikes. 231 married people bought bikes while 250 single people bought bikes
## Dashboard visualization
The conclusion and recommendation where derived from this dashboard ![image](https://github.com/Faithjf/Data_Analysis_And_Visualization_Excel/blob/main/Bike_purchaes_dashdoard-2.jpg)

## CONCLUSION AND RECOMMENDATIONS
After carefully considering the report analysis, I noticed that on the average based on the information provided in this data, bike purchases aren’t having enough sales because, out of 1000 individuals surveyed, only 481 purchased bikes. Therefore, there’s need to attract more buyers by means of advertisement, such as: Tv broadcast, social media, etc.

## RECOMMENDATIONS:
1. Since the younger generation (youths) made more purchases, I recommend a target campaign to draw the attention of more youths into buying bikes. 
2. Also, I recommend getting more perks to customers in North America, as they own a bunch of bike purchases, this is to retain and encourage them to bring more customers.
3. Creating awareness for new customers through advertisement, irrespective of their marital status and gender, while paying attention the people that commute 0-1 miles. 
## Excel functions used in this project:
-	Countif
-	Nested if statement
-	Text trim
-	Find and replace
-	Remove duplicates
-	Sort and filtering
-	Pivot charts and tables
