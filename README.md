Rossmann operates over 3,000 drug stores in 7 European countries. Currently, 
Rossmann stores managers are tasked with predicting their daily sales for up to six 
weeks in advance. Store sales are influenced by many factors, including promotions, 
competition, school and state holidays, seasonality and locality. With thousands of 
individual managers predicting sales based on their unique circumstances, the 
accuracy of the results can be varied.
The problem statement was to forecast the “Sales” column for the test data. For the 
purpose we are provided with historical sales data for 1,115 Rossmann stores. We 
provided two datasets i. Rossmann Stores Data.csv – gives historical data including 
sales and ii. Store.csv – supplement information about the stores.
The first step in the analysis involved understanding the data, exploring the data,
identifying the variables, and then performed data cleaning like removing the 
duplicates, anomaly correction, changing datatype of columns, looking for any null
values and tackling them, filtering records, outlier detections and ways to dealing 
them. For the purpose, we import necessary python libraries, load the datasets, and 
used various pandas and NumPy built in functions.
The second step involved analyzing the different numerical and categorical features
and show the analyzed result using different visualization charts like bar graph,
clustered bar chart, box plot, pie chart, distplot, scatterplot etc. For this purpose, we 
used data visualization libraries – seaborn and matplotlib. 
The third step involved feature engineering – dealing with categorical variables, 
multicollinearity, and at last after all these Data preprocessing steps we go for 
applying the Machine Learning algorithm to build a model that will predict the sales 
for the test data. For the purpose, we used Supervised ML models like Linear 
Regression, Ridge, Lasso, Decision Tree and Random Forest etc. and calculated 
evaluation metrics to check the performance.
The Final step involved is summing up the key observations and insights developed 
during the analysis and ML Model selection. Some key takeaways were: the relation 
between the sales and customers is sort of linear, i.e., the sales are increasing with 
the increasing number of customers which is obvious. Sales is more when 
Promo/Offers are running on stores, Highest sales recorded in December due to 
Christmas and New Year. Store with Assortment level ‘b’ has the highest sales. At 
last, based on the evaluation metrics we select the Random Forest Hyperparameter 
Tuned Model as it is giving the best accuracy compared to other regression models
