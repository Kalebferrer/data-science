## data-science-repo
<img src="./images/ds.png" width="25%" height="10%">

Welcome to my data science repo.

### Projects
1. [**heart disease**](https://github.com/Kalebferrer/data-science/tree/main/heart-disease) - predict if a new patient will have heart disease
<br> **Description:** supervised machine learning algorithm - K nearest neighbor (KNN)
<br> **Results**: 82% accuracy

2. [**credit card customer segmentation**](https://github.com/Kalebferrer/data-science/tree/main/credit-card-segmentation) - segment credit card customers based on spend and attributes
<br> **Description**: unsupervised machine learning algorithm - k means clustering
<br>**Results**: Segmented the data into clusters and provide commentary on similar characteristics of each cluster to deploy targetted marketing strategies.

3. [**predicting insurance costs**](https://github.com/Kalebferrer/data-science/tree/main/predicting-insurance-costs) - construct a predictive model for total medical insurance cost
<br> **Description:** predict medical cost to allow hospitals to predict revenue and plan procedures needed by patient population - linear regression model
<br> **Results**: regression coefficients of 'age', 'bmi', and 'is_smoker' and their efffects on charges

4. [**stochastic gradient descent**](https://github.com/Kalebferrer/data-science/tree/main/stochastic-gradient-descent) - predict best time to go to the gym to have no wait time on machines
<br> **Description:**  60,000 observations gym dataset with timestamp, number of people and other determinent characteristics - stochastic gradient descent on linear regression
<br> **Results**: Best time to go: 5-8 am on Saturdays, Fridays, Tuesdays. Busy times are around January (New Years) and August (school semester begins). ~9am, ~5pm, ~11pm are busiest times.

5. [**logistic regression model in python**](https://github.com/Kalebferrer/data-science/tree/main/logistic-regression-model) - classify heart disease that uses logistic regression model
<br> **Description:**  predict if a patient has heart disease by using a logistic regression classification model. [Data: Cleveland Clinic Foundation](https://archive.ics.uci.edu/dataset/45/heart+disease)
<br> **Results**: Test accuracy 75%, sensitivty was 79% and specificity was 72%.

6. [**decision tree and random forest model**](https://github.com/Kalebferrer/data-science/tree/main/decision-tree-model) - predict productivity performance of working teams.
<br> **Description:**  find features that help increase employee productivity. [Data: UCI Machine Learning repository - garment production](https://archive.ics.uci.edu/dataset/597/productivity+prediction+of+garment+employees)
<br> **Results**: Increasing incentives would help boost productivity as it plays a vital role and was found to be the root of every tree we produced.

7. [**optimizing ml models**](https://github.com/Kalebferrer/data-science/tree/main/optimizing-ml-models) - machine learning optimization tasks to improve/optimize a model to predict the extent of fire damage to a forest
<br> **Description:**  Walk through tasks for optimizing ML models (Feature engineering, model selection, cross validation, regularization).  [Data: UCI Machine Learning repository - forest fires](https://archive.ics.uci.edu/dataset/162/forest+fires)
<br> **Results**: Among candidate models, the backward selection using two features performs best, with an average MSE of -2.17. However, it's on log-scale so this suggest that predictions are off by a magnitude of 2. On the surface, this suggests that the models are not good predictors. However This problem is known to be a difficult one. The extreme skew in the outcome hurts many of the assumptions needed by linear models. This demonstrates that machine learning is not a universal fix and that several problems in data science have chararateristics that makes prediction difficult.
