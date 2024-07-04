# Cardiovascular-Disease-Detection
The analysis with the goal of applying multiple classification techniques (Logistic Regression, Decision Tree, KNN) to conduct a cardiovascular disease detection, has been studied. This
project attempts to improve the accuracy of cardiovascular disease identification by utilizing data science approaches in partnership with cardiologist Professor Suat Birtan. In different classification analyses, the details of which will be given later in the report, the dataset containing different characteristics collected by Prof Suat Birta from 70000 patients was used. Many health-related characteristics are included in this dataset, such as patient' gender, age, height, weight, important physiological indicators like blood pressure (high and low), cholesterol, and glucose levels, and lifestyle choices including drinking alcohol, smoking, and engaging in physical activity.


![image](https://github.com/tugceozgirgin/Cardiovascular-Disease-Detection/assets/93055813/cf5856ad-5951-4fd1-b7a5-f839ec9085ef)


The study uses a comparative comparison of three different classification algorithms, Decision Tree, K-Nearest Neighbors (KNN), and Logistic Regression.When we compare all algorithm performance metrics, we observe that the Logistic Regression approach gives the best results in terms of precision. From the perspective of Accuracy metric, we observe that the Decision Tree approach gives better results. And from the perspective of the recall metric, we observe that the KNN Classification approach gives better results. Since as we mentioned,our main goal is to reduce false negatives, that is, to create a model with high recall. We can say that the best performance for this purpose is the KNN model. We can also observe this from the Fβ scores where we got beta 2, KNN also is worse according to Fβ. This might be the case because KNN is able to capture the nuances of the data, which show complicated patterns that aren't well-separated by linear bounds.


