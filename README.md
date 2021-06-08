# Phase2-project-
## Business Problem 
One of HGTV Network's couples is moving to King Country and HGTV does not want to lose them.  Instead of letting them go, HGTV will be using the King county's data set, which includes over 21k entries, to figure out what type of show would fit with the couple's new areas. The most important indicator is cost since that will be used to determine the budget. 
## Data Cleaning 
### Missing values
1.	Waterfront null values became 0.0
2.	View null values became 0.0
3.	Yr_renovated null values became 0.0
4.	Sqft_basment “?” values became sqft_living  -  sqft_above
### Values dropped 
1.	Homes with more than 5 bedrooms
2.	Homes with less than 1 bathroom
3.	Condition column 
4.	Date when month_year was created 
5.	Sqft_basement when new_sqft_basement was created 
## EDA
## Modeling 
## Conclusion 

## Future Work 
1.	Figure what makes a grade 8 home vs grade 13
2.	Compare our target home type  to the target home of other shows on HGTV 
3.	Going to the location and create our own view column for certain areas 
4.	Reverse engineer the Linear regression to see what type of home we can get with in a price range 


