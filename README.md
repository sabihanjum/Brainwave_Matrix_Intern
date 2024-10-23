# Fake News Detection using Machine Learning

Fake news on different platforms is spreading widely and is a matter of serious concern, as it causes social wars and permanent breakage of the bonds established among people. A lot of research is already going on focused on the classification of fake news.

Here we will try to solve this issue with the help of machine learning in Python.

Before starting the code, download the dataset by clicking the link.
Dataset Link : https://www.kaggle.com/datasets/subho117/fake-news-detection-using-machine-learning.

**Steps to be followed**
Importing Libraries and Datasets
Data Preprocessing
Preprocessing and analysis of News column
Converting text into Vectors
Model training, Evaluation, and Prediction
Importing Libraries and Datasets
The libraries used are : 

Pandas: For importing the dataset.
Seaborn/Matplotlib: For data visualization.

**Data preprocessing**
The shape of the dataset can be found by the below code.

**Preprocessing and analysis of News column**
Firstly we will remove all the stopwords, punctuations and any irrelevant spaces from the text. For that NLTK Library is required and some of it’s module need to be downloaded.

**Converting text into Vectors**
Before converting the data into vectors, split it into train and test.

Model training, Evaluation, and Prediction
Now, the dataset is ready to train the model.

For training we will use Logistic Regression and evaluate the prediction accuracy using accuracy_score.

**Conclusion**
Decision Tree Classifier and Logistic regression are performing well.



