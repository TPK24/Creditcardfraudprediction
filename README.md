# Creditcardfraudprediction

### Credit card fraud prediction

#### Project Overview
```
The Credit Card Fraud Detection project is designed to identify fraudulent transactions using machine learning techniques.
This classification model leverages historical transaction data to detect and flag potentially fraudulent activities,
thereby enhancing security and reducing financial losses for credit card companies and their customers.
```
### Create a new Environment

```
conda create -p venv python==3.7 -y
```

#### Requirements
```
To run this project, you need the following software and libraries:
Python version 3.7 or higher
scikit-learn >= 1.0.0
numpy >= 1.21.0
pandas >= 1.3.0
imblearn >= 0.8.1
matplotlib >= 3.4.0
seaborn >= 0.11.0
IPython
```

### Software and tools requirements

1. [Github Account](https://github.com/TPK24/Creditcardfraudprediction)
2. [VSCodeIDE](https://code.visualstudio.com/)
3. [GitCLI](https://git-scm.com/)


### How to setup the project on local machine
```
Cloning the Repository
Local/folder/path>git clone https://github.com/TPK24/Creditcardfraudprediction.git
```

### Install Dependencies
```
You can install the packages using pip install -r requirements.txt
```

### Model Serialization file(pickle file)

[classifimodi.pkl](https://github.com/TPK24/Creditcardfraudprediction/tree/main/Models)

### Dataset

[Creditcard fraud](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

###Machine Learning Process

1. Exploratory Data Analysis

   Tasks:

        Loading the Dataset.
        performing Statistical summaries - Exploring data and performing discriptive statistics.
        Visualizing data Distributions and Relationships.
   
   [Exploratory Data Analysis(EDA).ipynb](https://github.com/TPK24/Creditcardfraudprediction/blob/main/notebook/Exploratory%20Data%20Analysis(EDA).ipynb)
   
*** Detailed explanations on various techniques used and its outputs are present in the above file

3. Data Preprocessing

   Tasks:

        Data cleaning - Handling Missing values, Treating Duplicate values, Outliers.
        Split the dataset into training and test sets - Spliting Data into Training and Test data for model training
   
   [Data Preprocessing.ipynb](https://github.com/TPK24/Creditcardfraudprediction/blob/main/notebook/Data%20Preprocessing.ipynb)
   
4. Model Training and Evaluation

    Tasks:

        Feature Scaling - Standard scaling adjusting the range and distribution of features so they are on a similar scale. 
        Balancing the Dataset. Treating the imbalanced data with SMOTE() method so that model can predict accurate results
        Model training - Random Forest CLassifier Algorithym used for training the model the reason behind using this
                         algotithym it works well with outliers and imbalanced data
        Model Prediction - predicting the model on the test data
        Model Evaluation - Classification Reoprt, Precision recall Curve and Precision recall score metrics used to evaluate the data
        Feature Importance. To find out features which have played important role in model prediction
   
   [Model Training & Evaluation.ipynb](https://github.com/TPK24/Creditcardfraudprediction/blob/main/notebook/Model%20Training%20%26%20Evaluation.ipynb)
   
 6. New data prediction
    
    Task:
    
        Prediction of data on the pickle file
    
    [New data prediction.ipynb](https://github.com/TPK24/Creditcardfraudprediction/blob/main/notebook/New%20data%20prediction.ipynb)
      
