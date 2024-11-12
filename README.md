# DS3000
## Description:
We researched the impact of corn production on the environment, as well as how the environment impacts corn production.
There are numerous factors that contributes to the efficiency of corn production i.e. climate, technology, surrounding crops, and we wanted to see if we could identify patterns that could explain the relationships. Our research focused on the effects of drought on corn production.


The data for this project was obtained from the USDA and the US drought monitor. Data with information regarding the production of corn from ethanol was
used to generate a logarithmic regression. The data sets with corn supply and drought data were cleaned in order to be able to merge them all into one dataset. Column types and names were changed in order to have a standardized dataset. Datasets were then combined using an inner join on the state and year columns.
In order to split the dataset we decided to invoke the train-test-split method from the sklearn library. Before running the models we also normalized our dataset. The four models we chose to use were the
logarithmic regression model, the K-nearest neighbors, support vector machines, and the random forest regression. These algorithms will be used to predict the amount of corn produced by each state based on the
drought data of each state, and then used the value found to predict the amount of ethanol produced in the following years. 


## Technologies Used
Pandas: Data cleaning and aggregation Seaborn: Creating visualizations Matplotlib: Customizing graphs


## Machine Learning Models: 
Support Vector Machine, KNN, Random Forest Regressor, and Logistic Regression 
