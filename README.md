# Credit_Risk_Analysis
Predict credit risk with machine learning models that we would build and evaluated using python.

# Overview of the analysis:

The purpose of this Analysis is to test how machine learning models are predict Credit risk by using resampling Models, SMOTEENN Algorithm and Ensemble Classifiers.

# Results

# Random oversampling
![Random_oversampling](https://user-images.githubusercontent.com/77947860/164845049-23f1edee-889b-45a5-a4b8-a973428e7ce0.png)

Balanced Accuracy Score : 0.6366972052004142
high risk performance:
- precision is very low(0.01)
- recall is good(0.62)

low risk performance:
-  precision is perfect(1.00)
-  recall is good(0.65)

# Smote

![Smote](https://user-images.githubusercontent.com/77947860/164838319-6cedb33f-4376-44e6-abc8-19cbf3aa5a06.png)

Balanced Accuracy Score : 0.6302712208564487
high risk performance:
- precision is very low(0.01)
- recall is good(0.62)

low risk performance:
- precision is perfect(1.00)
- recall is good(0.64)

# Cluster Centroid

![cluster](https://user-images.githubusercontent.com/77947860/164838638-c3dc25ec-99fd-4711-83af-c90996a99755.png)

Balanced Accuracy Score: 0.6302712208564487

high risk performance:
- precision is very low(0.01)
- recall is good(0.61)

low risk performance:
- precision is perfect(1.00)
- recall is low(0.45)

# Smoteen
![smotten](https://user-images.githubusercontent.com/77947860/164839768-d1ca6831-826b-451c-809b-45370adf8182.png)

Balanced Accuracy Score: (0.5293318990697431)

high risk performance:
- precision is very low(0.01)
- recall is great(0.70)

low risk performance:
- precision is perfect(1.00)
- recall is fair(0.57)

# Balanced Random Forest Classifier
![balanced_random](https://user-images.githubusercontent.com/77947860/164842618-ed1f79df-f207-44d7-b1cd-0578c703602c.png)

# Balanced Accuracy Score: 0.7877672625306695
high risk performance:
- precision is  low(0.03)
- recall is good(0.70)

low risk performance:
- precision is perfect(1.00)
- recall is great(0.87)

# Easy Ensemble Classifier

![easy_classifier](https://user-images.githubusercontent.com/77947860/164844200-25925b2d-12fc-41f0-a7d6-d8c942138b32.png)

# Balanced Accuracy Score: 0.925427358175101

high risk performance:
- precision is  low(0.07)
- recall is great(0.91)


low risk performance:
- precision is perfect(1.00)
- recall is great(0.94)

# Summary
The F1 score can be characterized as a single summary statistic of precision and sensitivity(recall). Given this, the F1 score is a great measurement to gauge model performance. Based on F1 scores the best forming model is the Easy Ensemble Classifier with an average F1 score of 0.97. While the worst performing is Cluster Centroid with an average F1 score of 0.62.

Based on performance the Easy Ensemble Classifier model is greatly recommended for assessing credit risk.




