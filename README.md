# Human-Activity-Detection-LSTM-Divide-and-Conquer-
The project is aimed to build a predictor model that predicts human activities such as Walking, Walking Upstairs, Walking Downstairs, Sitting, Standing or Laying ( 6 class classification) using the Smartphone data.

* The complete dataset for this project was obtained from the below site
https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones

* The file Human Activity Recognition Prediction.ipynb contains Exploratory Data Analysis, T-SNE for visiualizing the data and I have fit the data with the classical Machine Learning models such as Logistic Regression,Linear SVC,RBF SVM Classifier,Decision Trees, Random Forest Dts ,GradientBoosting Dts and also Deep Learning model (LSTM). This is the first approach in which all the models are fed with the handcoded features (561 featrues). 

* The Image files are the T-SNE Visualizations of the data points with 6 classes.

* The file HAR Divide and Conquer Approach.ipynb contains a deep learning model which is fed with the raw signals, here first model is created to split data into dynamic and static activities and later two models are built to one for classifying static activitis and other for dynamic activitis.





<em>References:</em>

* The divide and conquer based Human Activity Recognition is based on the research <a href="https://www.researchgate.net/publication/324224939_Divide_and_Conquer-Based_1D_CNN_Human_Activity_Recognition_Using_Test_Data_Sharpening">paper.</a>
