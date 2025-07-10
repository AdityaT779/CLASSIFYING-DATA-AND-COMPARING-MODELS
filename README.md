# CLASSIFYING-DATA-AND-COMPARING-MODELS

Overview:

This project involved building machine learning models to classify URLs as Phishing or Legitimate based on URL length and presence of HTTPS. I used Logistic Regression and Random Forest to train on a dataset and compare their performances. Through this, I learned how to split data, train models, evaluate performance using metrics, and visualize results for comparison.

Steps in model building and comparison:

1. Loaded and cleaned the dataset using pandas.

2. Handled missing values in both Label and URL.

3. Encoded the 'phishing' and 'legitamate' labels.

4. Created the new features url_length and has_https.

5. Split the dataset into training and test sets.

6. Trained two models, Random Forest Classifier and Logistic Regressor.

7. Evaluated both models using Precision, Recall, and F1-score.

8. Generated confusion matrices to visualize prediction results.

9. Created a simple bar chart to compare both models’ performance.

