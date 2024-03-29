# Healthcare-Analytics

<br><b>To predict Days Stay in Hospital for patients using the patient health details and Hospital Details</b></br>

# Data 

<br><b>Data can be downloaded from : https://www.kaggle.com/vin1234/janatahack-healthcare-analytics-ii </br></b>
<br>It is a classification problem where Stay is target variable and it is updated to predict the stay patient will be in hospital for in below categories:</br>
<br>0 - 20 days </br>
<br>21-30 days </br>
<br>31-60 days¶ </br>
<br>60+ days </br>

# Task performed

<br><b><Task><b>1: Performed data cleaning like handling categorical features, null values, grouping category for a feature, downsampling to get all target labels have same number of records and not imbalanced.</br>
<br>2: Performing Exploratory Data Analysis by plotting and understanding the data and columns using graphs, finding outliers and how each column is related to target labels etc </br>
<br>3: Implemented Random Forest considering all features, top 15 features and also Hyperparameter Tuning and evaluate the modles using metrics</br>
<br>4: Implemented Logistic Regression removed all multicollinearity with Variable Inflation factor(VIF) and did Hyperparameter Tuning on top features and evaluated the models</br>
<br><br>5: Implemented Decision Tree considering all features, top 15 features and also Hyperparameter Tuning  by evalauating the models with metrics</br>
<br>6: Built XgBoost Classifier and also with HyperParameter Tuning and evaluated the models with metric</br>
<br>7: Implemented LSTM (Long Short Term Model) Deep Learning Model and evaluated the model with performance metric </br>

<br> Few Snapshots of Analysis and Model results </br>

<br>![image](https://user-images.githubusercontent.com/55294349/132805360-10cba71e-f532-4108-9263-032bf4465b76.png) </br>
<br><b> Majority of Data had bed Condition 2 or 3 where majority of Bed Condition with 2 value stayed for 21-30 days</br></b>

<br>![image](https://user-images.githubusercontent.com/55294349/132805382-3fc6f9eb-5d04-4abd-be9b-2c31cdbea2eb.png)</br>
<br><b> Majority of Data had records with Trauma cases with almost equal distribution for target labels except for 0-20 days label</br></b>
<br><b> For Emergency cases most of the data records are 0-20 days hospital stay </br></b>

<br>![image](https://user-images.githubusercontent.com/55294349/132805407-79270b68-85fb-4098-aae6-f76c3bd4dc01.png)</br>
<b><br> Majority of cases are of Moderate severity of illness with equal distribution of records over different target lables. </br></b>

<br>![image](https://user-images.githubusercontent.com/55294349/132805487-4e443296-da64-4907-80fd-6f698866b531.png)</br>
<b><br> Admission Deposit median is 4500 INR and there are outliers randing outside the highest and lowest point</br></b>

<br>![image](https://user-images.githubusercontent.com/55294349/132805507-76be4039-5bda-4548-b556-b58705344533.png)</br>

<b><br> Majority of operation was Gynecology for patients </br></b>

<br> ![image](https://user-images.githubusercontent.com/55294349/132805545-5f22ad8c-fa56-4bc6-a4d0-cf2beb8d1228.png) </br>
<b><br> 10K INR is the median bill for patient and highest point is 30K INR, there are many outliers </br></b>

<br>![image](https://user-images.githubusercontent.com/55294349/132971853-3fa46c4a-87d0-49c1-b02b-eb67cb3352bf.png)</br>
<br><b> Random Forest and XgBoost Classifier both with HyperParameter Tuning are the better models giving good results </br></b>
