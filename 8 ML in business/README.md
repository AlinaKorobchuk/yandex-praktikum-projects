# Choosing a location for a well

### Data
Oil samples in three regions: each with 10,000 fields (geological exploration data)

**Signs**

- id — unique identifier of the well;
- f0, f1, f2 - three signs of points (it doesn’t matter what they mean, but the signs themselves are significant);
- product — volume of reserves in the well (thousand barrels).

### The goal of the project
Building a machine learning model that will help determine the region where mining will bring the greatest profit.

Steps to select a location:

- Deposits are searched for in the selected region, and the characteristic values ​​are determined for each;
- Build a model and estimate the volume of reserves;
- Deposits with the highest estimated values ​​are selected. The number of fields depends on the company’s budget and the cost of developing one well;
- Profit is equal to the total profit of the selected fields.
  
### Completed tasks

Data preparation, data analysis, identifying dependencies between features, visualization, selection of parameters for prediction models, training several models (linear regression, random forest, decision tree), testing on a test sample using RMSE, calculating profits and risks using the bootstrap technique.

The project is finished.

### Key takeaways:

The second region is proposed for field development.

### Libraries used

Pandas, sklearn (LinearRegression, RandomForestRegressor, DecisionTreeRegressor, train_test_split, mean_squared_error, StandardScaler, GridSearchCV, ), matplotlib, seaborn, scipy.
