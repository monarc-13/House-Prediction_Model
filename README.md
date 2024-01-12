# House-Prediction_Model
# Introduction
This project focuses on developing a Machine Learning model to predict home prices in Bangalore, India, utilizing a dataset obtained from Kaggle.com.

Key Data Science Concepts Employed in this Project:
- Data loading and cleaning
- Outlier detection and removal
- Feature engineering
- Dimensionality reduction
- Gridsearchcv for hyperparameter tuning
- K-fold cross-validation

## Technology and Tools Used
- Python
- Numpy and Pandas for data cleaning
- Matplotlib for data visualization
- Sklearn for model building
- Google Colaboratory Notebook

## Steps
1. **Model Building with sklearn and Linear Regression:**
   - Utilize the Bangalore home prices dataset from Kaggle.com.

## Detailed Steps:

### Step #1: Import the Required Libraries
Ensure that necessary Python libraries are imported for the project.

### Step #2: Load the Data
Load the dataset from Kaggle.com into the project.

### Step #3: Understand the Data
   - Drop unnecessary columns.

### Step #4: Data Cleaning
   - Check for NA values.
   - Verify unique values of each column.
   - Validate the correctness of values (e.g., ensure that a 23 BHK home with 2000 sqft size is considered incorrect).
   - Feature Engineering.
   - Dimensionality Reduction.
   - Outlier removal using domain knowledge (e.g., 2 BHK price < 3 BHK price, size per BHK >= 300 sqft).
   - Outlier removal using standard deviation and mean.
   - One Hot encoding.

### Step #5: Build Machine Learning Model
Utilize sklearn to construct a machine learning model, with a focus on linear regression.

### Step #6: Testing The Model
Test the model with relevant data to evaluate its performance.

### Step #7: Export the Model
Save the trained model for future use.

### Step #8: Export Any Other Important Info
Export any additional information that may be crucial for reproducing or understanding the results.

## Dataset Reference
Dataset CSV file: [Bengaluru_House_Data.csv](Bengaluru_House_Data.csv)

## Reference
Used Simplilearn(Data Science Collaboration with IIT Kanpur) for guidance throughout the project.
