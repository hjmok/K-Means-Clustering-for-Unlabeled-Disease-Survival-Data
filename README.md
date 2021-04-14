# K-Means-Clustering-for-Unlabeled-Disease-Survival-Data

The purpose of this project is to demonstrate the application of K-Means Clustering on a mostly unlabelled dataset. This unsupervised learning method can lead to clusters that may indicate survival or death when infected with certain respiratory diseases (COVID19, SARS, ARDS, Streptococcus).

## Dataset and Library
ScikitLearn and PySpark's KMeans modules was used to create the models.

The dataset consisted of 8 relevent columns with 372 rows of patient data, including the survival label. However, majority of the survival column was unlabeled (256 rows), so K-means was used to perform unsupervised learning on the dataset. After removing the other remaining null values and the survival column, the final dataset was 185 rows by 7 columns as seen below.

Please find the dataset in the following link: https://www.kaggle.com/bachrr/covid-chest-xray 

## Results
The model was able to successfully form two clusters, however it is difficult the evaluate the accuracy due to the lack of labels on the survival. In addition, the final cluster centroids contain far more coordinate points than the original dataset due to One Hot Encoding all the categorical data (Finding, View, X-Ray, and Location columns)

Please visit the following link for the resulting images: https://hjmok.github.io/josephmok_portfolio/#/DS
