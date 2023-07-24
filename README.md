# credit-risk-classification
Module 20 Challenge for the Vanderbilt Data Analytics Bootcamp 2023

# Code from Documentation
The cell 
```
# Import the RandomOverSampler module form imbalanced-learn
from imblearn.over_sampling import RandomOverSampler

# Instantiate the random oversampler model
# # Assign a random_state parameter of 1 to the model
ros_model = RandomOverSampler(random_state=1)

# Fit the original training data to the random_oversampler model
# https://imbalanced-learn.org/stable/references/generated/imblearn.over_sampling.RandomOverSampler.html
X_res, y_res = ros_model.fit_resample(X_train, y_train)
```
contains code adapted from [this page](https://imbalanced-learn.org/stable/references/generated/imblearn.over_sampling.RandomOverSampler.html). 