# Credit-Risk-Analysis

## Purpose
Using Python and Machine Learning, we were able to train and test data to fit into a model that will most effectively predict credit risk.

## Results
Here are the results of the six different models we tested with our data. Each model has the accuracy score in addition to their precision and recall scores.


- Random Oversampling
accuracy score: 66.2%

![Screenshot 2022-12-07 at 9 32 02 PM](https://user-images.githubusercontent.com/109987269/206350069-77bda7e6-a444-43a9-8210-dd27cec2cad0.png)

- SMOTE Oversampling
accuracy score: 65.8%

![Screenshot 2022-12-07 at 9 33 20 PM](https://user-images.githubusercontent.com/109987269/206350209-3d73bb70-1678-43d5-8543-7435925a0558.png)

- Undersampling 
accuaracy score: 54.4%

![Screenshot 2022-12-07 at 9 34 23 PM](https://user-images.githubusercontent.com/109987269/206350331-10e370de-3194-4f26-9067-0aa04bd694cd.png)

- Combination(Over and Under) Sampling
accuracy score: 64.4%

![Screenshot 2022-12-07 at 9 35 13 PM](https://user-images.githubusercontent.com/109987269/206350439-ac2d25dc-9526-46d0-b893-06352bb02991.png)

- Balanced Random Forest Classifier
accuracy score: 78.8%

![Screenshot 2022-12-07 at 9 36 25 PM](https://user-images.githubusercontent.com/109987269/206350559-f08aa282-cfd3-4370-b79a-ff059241c811.png)

- Easy Ensemble AdaBoost Classifier
accuracy score: 93.1%

![Screenshot 2022-12-07 at 9 37 01 PM](https://user-images.githubusercontent.com/109987269/206350635-645f4207-1f09-4a5b-ad2c-38de7647745a.png)

## Summary

We were able to train and test our data to fit into our six different models to test their accuracy. For this data set, we recommend to use the Easy Ensemble AdaBoost Classifier since it had the highest accuarcy score between the six models. Not only did it have the highest accuracy, but it had the highest precision and recall scores meaning it will most effictavely calculate credit risk.
