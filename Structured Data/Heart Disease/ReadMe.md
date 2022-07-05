# Machine-Learning

HEART_DISEASE_ANALYSIS

In this project i have built an model by using various sklearn libraries to predict whether a person have heart disease or not by using few medical parameters.

I have builted model by using various steps right from the cleaning of the data till the model predictions.

The Steps i have gone through is :
* 1. Getting Data Ready ( Data Preprocessing )
* 2. Picking a model suitable to our problem ( in this case classification is our problem)
* 3. Fit the model to the data to make predictions
* 4. Evaluate the model
* 5. Imporve through Experimentation
* 6. Save and reload the trained model

I have also used matplotlib for clear visualization between data and to compare the common relationship between different columns of the dataset

![image](https://user-images.githubusercontent.com/91750738/174722314-86770bff-6f92-4084-94b6-0584fc669450.png)

![image](https://user-images.githubusercontent.com/91750738/174722371-374b51ff-de98-47da-b78f-8f540669c272.png)

In this project i have used all the libraries available for the classification problems:
1. Logistic Regression
2. Random Forest Classifier
3. Linear SVC
4. KNN Neighbours Classifier

While testing all the models **Logistic Regression** aims for the highest accuracy than other 3 model.

**For further improving the trained model**

I have used Hyperparamters Tuning by using cross-validation:
1. BY hand
2. RandomSearchCV
3. GridSearchCV


**Feature Importance**

At the last i have removed the columns those who have negative value in the correlation matrix and trained the data again by using the new dataset by droping those columns.
