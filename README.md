# Diabetes-Prediction-Tool
The dataset used is the Pima Indian dataset sourced from from the National Institute of Diabetes and Digestive and Kidney Diseases. The purpose of the dataset is to make a diagnostic prediction of whether a patient has diabetes, based on specific diagnostic measures included in the dataset. It consist of several medical predictor (independent) variables and one target (dependent) variable, Outcome. Independent variables include the number of pregnancies the patient has had, their BMI, insulin level, age, and so on.

Before building the diabetes prediction tool, I went through a few steps to understand the dataset.

The first visualization is a heatmap where each cell represents the correlation between the corresponding pair of columns in the dataset. The color intensity and annotation provide visual cues about the strength and direction of the correlation. Positive correlations are displayed in shades of green, negative correlations in shades of red, and stronger correlations with higher intensity. 

## Visualized correlations: Heatmap
![image](https://github.com/Habeneheir/Diabetes-Prediction-Tool/assets/131387175/89f7f880-462a-4256-9c1e-f3ef62152659)
## Distribution of diabetes classes
![image](https://github.com/Habeneheir/Diabetes-Prediction-Tool/assets/131387175/d06358bb-8654-4762-8f09-fdbe704c0628)


# Using Decision Tree
Decision trees can be used to diagnose diabetes by building a tree based on a set of input characteristics that are relevant to diagnosing diabetes. For example, a decision tree can be built based on characteristics such as age, BMI, blood pressure, and blood glucose levels. The tree can be trained on a dataset of both diabetic and non-diabetic patients and then use input functions to make predictions whether the new patient has diabetes or not. 

## Visual representation of the decision tree
![image](https://github.com/Habeneheir/Diabetes-Prediction-Tool/assets/131387175/2c2b1bae-fa04-4d75-8422-b6ae433d7758)

The Decision Tree Model has an accuracy of 0.701.

Using this model we can build a user-froendly interface that allows the user to enter their own feature values and get a prediction from the model about whether they are diabetic or not. When the user clicks the "Predict" button, the model will use the input values to make a prediction that will be displayed to the user.
 

## User-friendly interface to decision tree classifier output
<img width="426" alt="image" src="https://github.com/Habeneheir/Diabetes-Prediction-Tool/assets/131387175/5b23d214-0f5b-4772-8c9b-b3af287b875d">

The final result is a diabete prediction tool with 0.701 accuracy.

#### Here is an example of the prediction:
 <img width="188" alt="image" src="https://github.com/Habeneheir/Diabetes-Prediction-Tool/assets/131387175/8ff73384-b055-4895-86d4-bb2c5bd21926">
