# NBA Shot Prediction using Machine Learning (XGBoost) #

The provided Python script utilizes data analysis, visualization, and machine learning techniques to gain insights into individual NBA players' shot selection, using data on Kobe Bryant as an example. The code begins by performing exploratory data analysis and visualization techniques to analyze various aspects of Kobe Bryant's shots, including shot make distribution, location, time, period analysis, clutch time, performance analysis, and shot type analysis.

In addition to data exploration, the code employs and compares a number of classifiers for predictive modeling-- Specifically, logistic regression, random forests, AdaBoost, Gradient Boosting, and XGBoost. It preprocesses the data, selects relevant features, and splits it into training and testing sets. Because it performed the best (based on k-fold cross validation results), the XGBoost classifier is then trained on the training set and used to predict shot outcomes on the testing set. The model's accuracy is evaluated by comparing the predicted labels with the actual labels. By integrating machine learning with data exploration, the script provides a holistic approach to understanding Kobe Bryant's shot selection. It allows for both descriptive analysis through visualizations and predictive modeling using machine learning, enabling the identification of important factors contributing to shot success. 

As stated in the script, the model used here is quite simple and could certainly be further optimized-- Something I hope to do in the future when I have more time! That said, my goal with this script was to focus on EDA, and to demonstrate the impact that effective feature engineering can have on model performance. For more complex ensemble approaches, please keep an eye out for some of the other projects I'll be posting to GitHub in the coming weeks!

Finally, a big thank you to Seungjae Yeom for helping with this project! Your ideas greatly improved the end result. 
