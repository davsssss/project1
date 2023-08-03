# project1

Write-up summarizes major findings and implications at a professional level (5 points)  
Each question in the project proposal is answered with precise descriptions and findings (5 points)  
Findings are strongly supported with numbers and visualizations (5 points)  
Each question response is supported with a well-discerned statistical analysis from lessons (e.g., aggregation, correlation, comparison, summary statistics, sentiment analysis, and time series analysis) (5 points)

David: Compared popularity between fast food and dine in restaurants with Yelp Fusion API and yFinance. I categorized each restaurant by fast food or dine in prior to making comparisons. I found the average Yelp rating for each popular chain restaurant along with the annual revenue for the year 2022. I then tested the correlation between annual revenue and yelp reviews which returned a correlation coefficient of -0.54 signifying negative correlation. This shows that customers favor convenience over quality.

Alex: With regards to trends in delivery companies, the relationship between company annual revenue over years shows a clear positive correlation. Calculating for the correlation coefficient of each company showed that each company had a coefficient above .9 reflecting the clear demand and engagement with these services despite the price increase. It was interesting to see that although the age of consumers primarily lies within the 18-34 year old range, there was a more uniform user age for mealkit services than delivery services. Mealkit services were also preferred by females, where as delivery services were more evenly split, with the exception of DeliveryHero. This outlier is likely due to the fact that DeliveryHero does not operatre in the US, and cultural differences in the other regions may affect the gender distribution of their users.

William: Looked at trends in Household Median income for the years 2020 to 2021 and at how the Top 50 fast food chains did in systemwide sales for the same years. I started by creating two individual dataframes to have my information, and then utilized matplotlib to plot a bar graphs to compare 2020 median income to 2021 in roughly 43 types of households. Each category was specified by type of homeowner, race, age, region, or education background via the US Census data. In a majority of households, there was an increase in median income, however, the few types that had decreases were actually quite significant as it was among woman homeowners, and people who only did some college. Next, I looked at the systemwide sales in the US for the Top 50 fast food chains according to information provided by QSR Magazine. Similarly to income, most of the chains exceeded 2020 sales in 2021, but the ones that didn't exceed were often at least matching the prior year. I tried to then compare the increase in incomes to our increasing sales but was met with no correlation which actually makes a lot of sense. There are simply many variables that go into those numbers, and further research would need to be performed to really find a connection between the two. 
