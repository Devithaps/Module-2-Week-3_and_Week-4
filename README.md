Module 2 
Week 3 and week 4 
Problem Statement 

You are given the Diamonds dataset from the seaborn library. Using only NumPy and Pandas, perform the following tasks. 
1. Load the Diamonds dataset using seaborn. 
2. Store it in a Pandas DataFrame named df. 

Create a new DataFrame named premium_df that satisfies all the following conditions: 
•	• cut is either "Ideal" or "Premium" 
•	• color belongs to D, E, or F 
•	• clarity belongs to VS1, VS2, or IF 
•	• carat is greater than the median carat of the dataset 
•	• price is greater than the mean price of the dataset 

Using premium_df, create the following new columns: 
1. price_per_carat = price / carat 
2. volume = x × y × z 
3. value_score = Min–Max normalized price_per_carat 
4. log_price = natural logarithm of price 

Using premium_df, create: 
1. A scatter plot between carat and price, colored by cut 
2. A scatter plot between volume and price_per_carat, colored by clarity 
	3. A pair plot for: o carat 
	o price 
	o price_per_carat 
	o value_score 
