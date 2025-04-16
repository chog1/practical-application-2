**Business Understanding**

The key question in this case is "what drives the price of a car?" based on the attributes of a used car. My job is to identify the key features based on provided data set and identify a model that can predict the price so that used-car dealers can align inventory for improved sales.

In under to further understand the data I loaded the data file 'vehicles.csv'and reviewed columns and valuesm using

train.info()
train.head()

**Data Understanding**

1. Identified 'missing data' and plot it in bar chart
2. Identified Outliers for Year, Price and Odometer
3. Checked value counts for categorical variables return list of categories and barchart for visual purposes

**Data Preparation**

1. Dropped columns with limited data or not applicable ('id', 'VIN', 'size')
2. Dropped rows with missing values in 'price'
3. Removed outliers based on price
4. Handle missing values in odometer
5. Removed outliers based on odometer
6. Removed outliers based on year

**Modeling**

1. linear regression model
2. Lasso Regression attribute selection

**Evaluation**
based on extensive analysis of used car data, we have found that the most important feature predicting price is "Year"

Through model evaluation, the linear regression model with features including 'year' showed good model performance.

As a result I would highly recommend going forward that you adjust your car inventory with a strong emphasis ensuring that The 'year' is the latest as possible.
