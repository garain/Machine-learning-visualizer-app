# App link [![HitCount](http://hits.dwyl.com/garain/Machine-learning-visualizer-app.svg)](http://hits.dwyl.com/garain/Machine-learning-visualizer-app)

https://machine-learning-visualizer.herokuapp.com/

# Creator
Avishek Garain

# Machine Learning Visualizer Tool 

This is a machine learning metrics visualizer tool for binary and multi-class classification of data.
For Binary classification, Confusion Matrix, ROC Curve and Precision Recall curves can be visualized. 
For multi-class classification, only Confusion Matrix can be visualized.

# Guidelines if facing problems to open site

The app uses one heroku dyno, so it faces loading issues sometimes. Once you go to the site, and it shows connecting, but doesn't open after 15 to 20s, then simply reload the site. Once it shows connecting, open some other pre-opened tab of the browser window. Then come back to the site after 5 to 6 secs. It will open by then.

# Algorithms supported

1) Support Vector Machine (SVM)
2) Logistic Regression
3) Random Forest
4) Nearest Neighbors
5) Decision Tree 
6) Neural Net(MLP)
7) AdaBoost(Decision Tree Classifier kernel) 
8) Naive Bayes
9) Quadratic Discriminant Analysis(QDA)

# Working
1. Upload a .csv file.
2. The 1st column should contain the labels and every column should have a header. 
3. Select any one of the algorithms.
4. Select hyperparameters according to your choice.
5. Select any one metric at a time to display. (Only one at a time)
6. Press classify.
7. The label column should have heading 'type'.

# Raw data
To view your data select "Show Raw data" option.

# Default
By default UCL mushrooms dataset is loaded.

