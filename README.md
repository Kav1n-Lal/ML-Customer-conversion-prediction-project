# ML-Customer-conversion-prediction-project
### Video demo link [https://drive.google.com/file/d/1g5v_vPpegzNsQimDRPqKo9-sLPHf9h76/view?usp=sharing]
### Problem statement link https://docs.google.com/document/d/1a1fwt8JUVU5M_r3xO6GvIqNW0yH-wM9U/edit?usp=sharing&ouid=102777560562290734716&rtpof=true&sd=true
### Table containing all models used and its corresponding ROC-AUC and Accuracy Score

|    Model                        |  Train(ROC-AUC)   |  Test(ROC-AUC)   |  Accuracy      |    Remarks          |
| :------------------------------ |-------------------|------------------|----------------|--------------------:|
| logistic_regression_smote       |         0.90      |        0.89      |      0.81      |                     |
| logistic_regression_smoteenn    |         0.90      |        0.89      |      0.82      |                     |
| logistic_regression_smotetomek  |         0.90      |        0.89      |      0.81      |                     |
| decision_tree_smote             |       OV-0.99     |        0.68      |      0.87      |                     |
| decision_tree_smote             |        0.94       |       0.86       |      0.84      |hyperparameter_tuned |
| decision_tree_smoteenn          |        0.95       |       0.86       |      0.85      |hyperparameter_tuned |
| decision_tree_smotetomek        |        0.95       |       0.85       |      0.84      |hyperparameter_tuned |
| random_forest_smote             |        0.96       |        0.89      |      0.84      |hyperparameter_tuned |
| random_forest_smoteenn          |        0.96       |       0.89       |0.84            |hyperparameter_tuned |
| random_forest_smotetomek        |        0.96       |       0.89       | 0.84           |hyperparameter_tuned |

# Dataset balanced using smoteenn and ran using Decision tree algorithm has given the best accuracy of 85% and ROCAUC-0.95(TRAIN) / 0.86(TEST)
