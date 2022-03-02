# supervised-machine-learning-challenge
Supervised machine learning homework for GT Data Science Bootcamp!

## Predictions and analysis
### Prediction - unscaled data
I predict that the random forest classifier will perform better here. I believe this type of model will handle the unscaled data better since Logistic Regressions are vulnerable to overfitting. 
### Analysis - unscaled data, results
The Random Forest Classifier scored significantly higher than the Logistic Regression (64% compared to 51%). This matched my prediction. I did not expect the gap between the scores to be quite this wide - the Logistic Regression barely broke a 50% score!
### Prediction - scaled data
I predict that scaling the data will increase the Logistic Regression Score and will not significantly impact the Random Forest Classifier Score. As for which model will perform better with the scaled data, that is more difficult to predict since I think the two models will be competing on more even ground. Even though the Random Forest Classifier scored much higher than the Logistic Regression on the unscaled data, it did not get what I would consider a stellar score - only about 64%. I believe that, since the Logistic Regression will improve substantially while the Random Forest Clasifier will not, the Logistic Regression will get a higher score this time. *crosses fingers*
### Analysis - scaled data, results
The Logistic Regression performed better than the Random Forest Classifier while using the scaled data (76% to 64%). Also, the Random Forest Classifier got almost the exact same score with scaled and unscaled data. While this confirms my prediction, I am surprised at how much the Logistic Regression model improved! From 51% to 76% - quite a jump!
