 Hyperparameter Optimization:
we change in hyperparameters affected the training success and it was observed that more successful systems were obtained when the correct parameters were selected. Although the best parameters are different for each data set, if we talk about the currently used data set; The system is better at max_depth:30 concept: This may mean that the data is separate from each other. They may tend to be separate groups and may be more successful at higher depths. Considering the success of RandomForest, it seems that it is easier to adapt to algorithms with Tree logic such as ExtraTree...

According to the results, the most successful parameters in:

RandomForest
n_estimators=100
max_features: auto
max_depth: 30
criterion: gini
LogisticRegression
C: 10
solver: liblinear
KNeighbors
n_neighbors: 19
weights: uniform
metric: manhattan
GradientBoosting
n_estimators: 100
max_depth: 30
DecisionTree
max_depth: 30
criterion: gini
These parameters were found to be the most effective based on their own comparisons.

PCA
PCA caused loss of success for this data set in my experiments, but this does not mean that PCA will cause you to lose success every time. You can see that it increases your success in other data sets as well. From another perspective, it was observed that the data analysis and processing time was shortened due to the smaller data set (due to the use of PCA). 

According to the results, the most successful parameters in:

RandomForest
n_estimators=100
max_features: auto
max_depth: 10
criterion: gini
LogisticRegression
C: 10
solver: liblinear
KNeighbors
n_neighbors: 19
weights: uniform
metric: manhattan
GradientBoosting
learning_rate: 0.05
max_depth: 4
n_estimators: 200
DecisionTree
max_depth: 10
criterion: gini
splitter: random
These parameters were found to be the most effective based on their own comparisons.
