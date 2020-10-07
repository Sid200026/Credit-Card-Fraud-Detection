# Credit Card Fraud Detection

- Kaggle : https://www.kaggle.com/mlg-ulb/creditcardfraud

### Result

<img src="https://github.com/Sid200026/Credit-Card-Fraud-Detection/blob/master/Result.png" alt="Result">

## Methodology

I used ensemble learning to achieve a high F1-Score. The following algorithms were used

| Algorithm                                 | Precision | Recall   | F1-Score |
| ----------------------------------------- | --------- | -------- | -------- |
| Decision Tree                             | 0.282686  | 0.824742 | 0.421053 |
| Random Forest                             | 0.941176  | 0.824742 | 0.879121 |
| Support Vector Machine                    | 0.967742  | 0.309278 | 0.468750 |
| Multi Layer Perceptron                    | 0.552941  | 0.484536 | 0.516484 |
| Neural Network using Tensorflow and Keras | 1.000000  | 0.381443 | 0.552239 |

The final model was developed ensembling the above models and using RandomForestClassifier.

| Precision | Recall   | F1-Score |
| --------- | -------- | -------- |
| 0.977011  | 0.977011 | 0.977011 |
