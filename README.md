# Credit_Risk_Analysis
Libraries Used:

* scikit-learn
* imbalanced-learn

# Deliverable 1

![basline_confusion_matrix](https://user-images.githubusercontent.com/84817579/202877362-c422b062-cee7-4280-9673-1ef8f57df74a.png)

The Baseline Classification Report showed a low score compared to low risk loans

![Baseline_Classification_Rpt](https://user-images.githubusercontent.com/84817579/202877389-f03cbcc6-33ec-4b74-97f2-fe43a81b3fab.png)

# Baseline Imbalanced Classification Report

![Baseline_Imbalanced_Classification_Rpt](https://user-images.githubusercontent.com/84817579/202877404-f10c565b-a627-4f8e-bea6-39734f3dbede.png)

RandomOverSampler Technique

![RandomOverSampler_confusion_matrix](https://user-images.githubusercontent.com/84817579/202877427-a9deeece-7e49-4fa4-9270-007ceaec0135.png)

This one deteriorated the model

![RandomOverSampler_Rpt](https://user-images.githubusercontent.com/84817579/202877450-1ca3c851-a889-4ee9-9b84-72f46dbce5e6.png)

SMOTE Oversampling Technique

![SMOTE_confusion_matrix](https://user-images.githubusercontent.com/84817579/202877466-60d2bde3-ac46-4dec-8f34-6b9c017bd008.png)

![SMOTE_Oversampling_Rpt](https://user-images.githubusercontent.com/84817579/202877470-ca269756-d0ce-4e17-9a9d-442ecb4c50f1.png)


# Deliverable 2 - Use the SMOTEENN algorithm to Predict Credit Risk

Oversampling and Undersampling did produce a model to predict high-risk

![SMOTEENN_confusion_matrix](https://user-images.githubusercontent.com/84817579/202877515-c6114258-49b2-43f8-aa7c-4ce19cad9872.png)

![SMOTEENN_Classification_Rpt](https://user-images.githubusercontent.com/84817579/202877523-31912a2c-d494-4465-ab55-ca03abbaa9e1.png)

# Deliverable 3 - Use Ensemble Classifiers to Predict Credit Risk

## Balanced Random Forest Classifier

![RandomForestEnsemble_confusion_matrix](https://user-images.githubusercontent.com/84817579/202877551-2836b11e-494f-4769-b67a-bbb7f5839ded.png)

![Forest_Rpt](https://user-images.githubusercontent.com/84817579/202877555-e4868440-4f65-4b34-8632-4543390fc9e3.png)

## Balanced Random Forest Classifier

The Balanced Accuracy Socre for the Random Forest approach was 75.89%

![RandomForestEnsemble_confusion_matrix](https://user-images.githubusercontent.com/84817579/202877585-508fb255-1510-4ac9-bc76-dcb8bb5bf4fd.png)


![Forest_Rpt](https://user-images.githubusercontent.com/84817579/202877598-cbaaae0b-f3e2-4048-9b34-5ed163dc4b0a.png)


## Top 5 features of importance and bottom 5 features of least importance 

![features](https://user-images.githubusercontent.com/84817579/202877605-8458e77f-6b03-48b2-bf99-1593301e4eba.png)

## Easy Ensemble AdaBoost Classifier

![AdaBoostEnsemble_confusion_matrix](https://user-images.githubusercontent.com/84817579/202877640-ecdb236e-fbca-474f-bcf8-72f6dbd8f664.png)

![AdaBoost_Rpt](https://user-images.githubusercontent.com/84817579/202877648-a0746f77-fec1-4e2e-9764-c5b584451197.png)

## Summary

None of these techiniques helped for our goal of identifying high risk loans. 
