# Titanic
### Overview
The Titanic Website System is a dynamic web application that provides an engaging and informative experience centered around the historic RMS Titanic. Seamlessly integrating historical data with modern technology, the platform features a machine-learning model to predict survival probabilities based on user-input parameters such as passenger class, gender, and age. Beyond its predictive capabilities, the system serves as an immersive resource for individuals keen on exploring the rich history of the Titanic.

### Purpose
##### The specific objectives of the Titanic  are:
Implement a machine learning model trained on the Titanic dataset to predict survival probabilities.

### Technologies Used
Python
Data Science Libraries (NumPy, Matplotlib, Pandas, Seaborn, Scikit-Learn)

### Stages of the Project
#### 1. Data Collection and Preparation
The first stage involved collecting the Titanic dataset.

#### 2. Exploratory Data Analysis (EDA)
###### During the EDA stage, a comprehensive analysis of the dataset was conducted.
###### And EDA contains 2 stages
   ###### - Understanding:
   Here we should know about this data, and try to understand all Features  
   ###### - Understanding and Analysis data Using Plots
   This included data visualization, statistical summaries, and correlations between variables.
  Finaly in this Stage: Exploring the data helped identify patterns, trends, and relationships that could influence the survival prediction process.

#### 3. Cleaning
  ###### - Feature Engineering
   Feature engineering involved selecting and transforming the most relevant variables for  models. This stage helped improve the models' accuracy. 
   
  ###### - Handling Missing Values
   Filling All Missing values and make sure that all future data will be handling before enter to the model, we do this stage to remove ant interpting for model.
     
#### 4. Splitting 
   Here we splitting data to training and test. To train and test model with them.
    
#### 5. Model Building and Training
   In this stage, We Building All Models will be used, And train them with trainging data.

#### 6. Model Evaluation
The trained model was evaluated using various evaluation metrics such as accuracy, precision, recall, and F1-score. Cross-validation techniques were employed to ensure the model's robustness and generalizability. The evaluation results provided insights into the model's performance and helped identify areas for improvement.

#### 7. Prediction and Deployment
Once the model was deemed satisfactory, it was used to make predictions on new, unseen data. The model's predictions were then deployed for practical use, such as predicting survival probabilities for passengers in real-world scenarios.
