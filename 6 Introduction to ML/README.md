# Tariff prediction

### Data
Data on the behavior of customers who have already switched to certain tariffs.

**Description of data**

Each object in the dataset is information about the behavior of one user for a month. Known:
- calls — number of calls,
- minutes — total duration of calls in minutes,
- messages — number of SMS messages,
- mb_used — consumed Internet traffic in MB,
- is_ultra — what tariff you used during the month (“Ultra” - 1, “Smart” - 0).

### The goal of the project
Build a model that can analyze customer behavior and offer users a “Smart” or “Ultra” tariff

### Completed tasks

Data preparation, data analysis, identifying dependencies between features, visualization, selection of parameters for prediction models, training several models (logistic regression, random forest, decision tree), building a constant model, testing on a test sample.

The project is finished.

### Key takeaways:

For a system that recommends Smart or Morning tariffs to users, a decision tree model with a maximum depth of 7 is proposed

### Used technologies

Pandas, sklearn (LogisticRegression, RandomForestClassifier, DecisionTreeClassifier, train_test_split, accuracy_score, DummyClassifier), matplotlib, seaborn.
