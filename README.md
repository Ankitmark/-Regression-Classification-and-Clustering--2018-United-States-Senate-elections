# Regression-Classification-and-Clustering--2018-United-States-Senate-elections
Performing Regression, Classification, and Clustering on 2018 United States Senate elections demographic information.

Given the merged dataset (merged_train.csv), perform the following tasks:
1. Partition the merged dataset into a training set and a validation set using the
holdout method or the cross-validation method. How did you partition the dataset?
2. Standardize the training set and the validation set.
3. Build a linear regression model to predict the number of votes cast for the
Democratic party in each county. Consider multiple combinations of predictor variables.
Compute evaluation metrics for the validation set and report your results. What is the
best performing linear regression model? What is the performance of the model? How
did you select the variables of the model?
• Repeat this task for the number of votes cast for the Republican party in each
county.
4. Build a classification model to classify each county as Democratic or
Republican. Consider at least two different classification techniques with multiple
combinations of parameters and multiple combinations of variables. Compute
evaluation metrics for the validation set and report your results. What is the best 
performing classification model? What is the performance of the model? How did you
select the parameters of the model? How did you select the variables of the model?
5. Build a clustering model to cluster the counties. Consider at least two different
clustering techniques with multiple combinations of parameters and multiple
combinations of variables. Compute unsupervised and supervised evaluation metrics
for the validation set with the party of the counties (Democratic or Republican) as the
true cluster and report your results. What is the best performing clustering model? What
is the performance of the model? How did you select the parameters of model? How did
you select the variables of the model?
6. Create a map of Democratic counties and Republican counties using the
counties’ FIPS codes and Python’s Plotly library (plot.ly/python/county-choropleth/).
Compare with the map of Democratic counties and Republican counties created in
Project 01. What conclusions do you make from the plots?
7. Use your best performing regression and classification models to predict the
number of votes cast for the Democratic party in each county, the number of votes cast
for the Republican party in each county, and the party (Democratic or Republican) of
each county for the test dataset (demographics_test.csv). Save the output in a single
CSV file. For the expected format of the output, see sample_output.csv.

