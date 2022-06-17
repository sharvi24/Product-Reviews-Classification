# Product-Reviews-Classification

- Created a multi-class classification model for classification of 5K reviews into 20 product categories.
- Experimented with following 4 machine learning models, evaluated their accuracy and checked for the source of any potential issues.
    1. Logistic Regression
    2. (Multinomial) Naive Bayes
    3. Linear Support Vector Machine
    4. Random Forest
    
    LinearSVC and Logistic Regression perform better than the other two classifiers, with LinearSVC having a slight advantage with a median accuracy of around 65.64%.
    
- Analysed the discrepancies between predicted and actual labels using confusion matrix. Many of misclassified complaints are the ones that touch on more than one subject, such errors will always happen
- Used the chi-squared test to find the terms that are the most correlated with each of the categories and found them to be consistent within our expectation.
- Finally, printed out the classification report for each class (Precision, Recall, F1-score, Support)
