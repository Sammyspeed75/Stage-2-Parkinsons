# Stage-2-Parkinsons
**Parkinson’s disease** is a progressive disorder of the central nervous system affecting movement and inducing tremors and stiffness. It is a neurodegenerative disorder affecting dopamine-producing neurons in the brain. It has 5 stages to it and affects approximately 1% of individuals older than 60 years . There is no cure for the disease. Although, most patients can maintain a good quality of life with medications. In some patients, surgery can help improve symptoms. 

**Parkinsons is characterised  by various symptoms** .
<p align="center">
<img src="https://user-images.githubusercontent.com/68779543/138735867-52693f6d-d427-4ce9-8b9a-fc7589de27ea.png" width="799" heigth="805">


The link to the UCI ML Parkinsons dataset used is given below 
* [Parkinsons Disease Dataset ](https://archive.ics.uci.edu/ml/machine-learning-databases/parkinsons/)

  # 📌Goal
The main goal of this project is to use Python Machine Learning to build a classification model which can accurately detect the presence of Parkinson’s disease in a patient’s body based on the various feature inputs used to train the model.
  
 Abstract : Oxford Parkinson's Disease Detection Dataset
🚀 **WHATS IN THE DATASET?**

  Data Set Characteristics: Multivariate

  Number of Instances: 197

  Area: Life

  Attribute Characteristics: Real
  

  Number of Attributes: 23

  Date Donated: 2008-06-26

  Associated Tasks: Classification
  
  <h1 align="center"> Data Set Information</h1>
  
  <h2 align="center"> This dataset is composed of a range of biomedical voice measurements from 
31 people, 23 with Parkinson's disease (PD). Each column in the table is a 
particular voice measure, and each row corresponds one of 195 voice 
recording from these individuals ("name" column). The main aim of the data 
is to discriminate healthy people from those with PD, according to "status" 
column which is set to 0 for healthy and 1 for PD.

The data is in ASCII CSV format. The rows of the CSV file contain an 
instance corresponding to one voice recording. There are around six 
recordings per patient, the name of the patient is identified in the first 
column</h2>

👩‍🔬👩‍💻Workflow :
We will use the Google Colab Notebooks whih are popular data science tools to do our Model building.

1 Load the Dataset

2 Data Preprocessing

3 Splitting the dataset 

4 Training the model 

5 Testing The model

6 Determining accuracy

* Here we load all the libraries we will need to work with .

  ```
  import pandas as pandas
  from sklearn.preprocessing import MinMaxScaler
  from xgboost import XGBClassifier
  from sklearn.model_selection import train_test_split
  from sklearn.metrics import accuracy_score```
