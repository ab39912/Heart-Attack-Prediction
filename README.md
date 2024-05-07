# Heart-Attack-Prediction

A heart attack (cardiovascular disease) happens when the passage of blood to the heart muscle is unexpectedly blocked. According to WHO figures, 17.9 million people die each year from a heart attack. According to the medical study, human lifestyle is the primary cause of this heart disease. Aside from that, there are other significant markers that indicate whether or not a person is at risk of suffering a heart attack.
![](screenshots/heart.webp)</br>

About the heart - disease dataset:
The dataset is available on UC Irvine Machine Learning Repository .</br>

In this notebook, we intend to analyze data related to cardiac features of patients from the "heart.csv" dataset. This dataset provides various information about patients, including age, gender, blood pressure, cholesterol levels, electrocardiographic (ECG) features, and more. </br>

Dataset Information:
This dataset includes the following features:</br>
age: The age of the patient.</br>
sex: Gender of the patient (0: female, 1: male).</br>
cp: Type of chest pain.</br>
trestbps: Resting blood pressure.</br>
chol: Serum cholesterol.</br>
fbs: Fasting blood sugar > 120 mg/dl.</br>
restecg: Resting electrocardiographic results.</br>
thalach: Maximum heart rate achieved.</br>
exang: Exercise induced angina.</br>
oldpeak: ST depression induced by exercise relative to rest</br>

Flow of the Project:
1. The dataset 'heart.csv' was first understood using EDA and using libraries such as pandas and numpy.</br>
2. For visualisation libraries matplotlib.pyplot and searborn were imported.</br>
3. The csv file is read in the form of dataframe.</br>
4. The dataframe was understood using the info command.</br>
5. The dataframe was checked for null values.</br>
6. Heat map and histogram were plotted to check the correlation between the features.</br>
7. Dataframe was divided into parts X and y were X contained all the relative features and y the target.</br>
8. Later the dataset was split using train test split from sklearn library.
9. StandardScaler libary was used to transform the dataset.
10. Now different models were used such as Logistic Regression, Naive Bayes, Random Forest Classifier, Extreme Gradient Boost, K- Neighbors Classifier, Decision Tree Classifier, Suppport Vector Classifier </br>
11. Next we plotted the importance of features in the form of barplot</br>
12. A reciver Operating Characteristic Curve was also plotted.</br>
13. At last a dataframe was created to display the different models and their accurary.</br>
14. A Bar graph was plotted to display the models and their accuary. </br>
15. Finally stacked CV classifier was used to increase the accurary of the model. </br>

Conclusion:
1. We can conclude that SVM gave the best accuracy.</br>
2. From the features chest pain , excercise induced angina and cornory heart disease are the main causes of heart attack.</br>
3.  Ensembling technique increase the accuracy of the model.
