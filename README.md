# Covid-19 Detection using ML

This repository contains the code and dataset used in the research paper titled "Covid-19 Detection using Machine Learning Techniques". The goal of this project is to develop a model that can accurately detect the presence of Covid-19 from chest X-ray images.

## Dataset

The dataset used in this project is the [Covid-19 Radiography Database](https://www.kaggle.com/tawsifurrahman/covid19-radiography-database). This dataset consists of chest X-ray images from Covid-19 positive patients as well as patients with other respiratory diseases and healthy patients.
![Data_set](Data.jpg)


## Environment
We used **Python 3.6** for this project and implemented the code in **Jupyter Notebook**

## Code

The code for this project is written in Python and uses the Keras library for building the machine learning model. The code is available in the `covid_detection.py` file. You can run the code using the command: python covid_detection.py

## Data Visualisation
### Bar Plot
![Bar Plot](Visualisation1.jpg)
### Count Plot
![Count Plot](Visualisation2.jpg)
### Correlation
![Correlation](Correlation.png)

## Results

Our model achieved an accuracy of 95% on the test set. The detailed results are presented below.
### Accuracy comparision after Hyperparameter Tuning
![Accuracy comparision after Hyperparameter Tuning](hyperpearameter_Tuning.png)
### Accuracy of different Models
![Accuracy of different models](Accuracy.png)
### Execution Time for different models
![Execution Time for different models](Time.png)

## Conclusion

The study aimed to create a machine learning model for predicting COVID-19 using fewer features and tests. The study used four classification techniques and nine key features, with support vector machine and decision trees yielding the best outcomes.

## Contributors

-Svachuta Siva Sai Krishna Prasad Gollavilli
-Sravan Kumar Reddy Pebbeti
-Keerthana Krishnamoorthy


