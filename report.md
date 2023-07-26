# Report

## Overview
Overall, we found that our models predicted healthy loans perfectly and that they predicted high risk loans fairly accurately, with `f1-score`s close to 1.00. The model with over-sampled data predicted high-risk loans a little bit more accurately than it did without over-sampled data. 

## Accuracy, Precision, and Recall
<!-- how often the model is correct—the ratio of correctly predicted observations to the total number of observations. 
(TP + TN) / (TP + TN + FP + FN) -->
* **accuracy** - The accuracy of of model--the ratio of correctly predicted observations to the total number observations--was 0.99 with and without over-sampled data. 
<!-- the ratio of correctly predicted positive observations to the total predicted positive observations. 
TP / (TP + FP) -->
* **precision** - The precision of the model--the ratio of correctly predicted positive observations to the total predicted positive observations--was 1.00 for the healthy loan class with and without over-sampled data. Without over-sampled data, the precision was 0.87 and decreased to 0.86 with the over-sampled data. Regardless, 0.86-0.87 is still fairly high. 
<!-- the ratio of correctly predicted positive observations to all predicted observations for that class. 
TP / (TP + FN) -->
* **recall** - From a value of 1.00 without over-sampled data to a value of 0.99 with over-sampled data, the recall remained quite high for the healthy loan class. For the high-risk loan class, the recall actually increased quite a bit, going from 0.89 without over-sampled data to 0.99 with over-sampled data. 

## Recommendation
I would recommend this model for use by the company since it perfectly predicts healthy loans and predicts high-risk loans fairly accurately, with `f1-score`s that are close to 1.00. 