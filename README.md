# Credit-Card-Fraud-Detection-CodSoft-Project-2

🔍 This project aims to detect fraudulent credit card transactions using a Support Vector Machine (SVM) model.

## Project Overview
Credit card fraud detection is a critical issue in the financial industry. This project uses historical transaction data to build a model that can predict fraudulent transactions.

## Requirements
Python 3.x
pandas
numpy
scikit-learn
matplotlib
seaborn

## Dataset
📊 The dataset used in this project is fraudTrain.csv. It includes transaction information such as:

|             |info|       |
|-------------------------|---------------------|----------------|
| trans_date   | cc_num              | merchant       |
| category                | amt                 | first          |
| last                    | gender              | street         |
| city                    | state               | zip            |
| lat                     | long                | city_pop       |
| job                     | dob                 | trans_num      |
| unix_time               | merch_lat           | merch_long     |
| is_fraud |  trans_time                    |                |

## Project Steps
### 1. Data Loading and Preprocessing
- Loading Data: The dataset is loaded using pandas.
- Data Cleaning: Unnecessary columns are removed.
- Handling Dates: Convert date columns trans_date_trans_time and dob to datetime format.
- Encoding Categorical Variables: Label encoding is used to convert categorical variables like merchant, category, gender, and job into numerical format.
- Handling Missing Values: Rows with missing values are dropped.

### 2. Data Splitting
- Feature and Target Selection: Features and target variable are separated.
- Train-Test Split: The dataset is split into training and testing sets using train_test_split from scikit-learn.

### 3. Model Training and Evaluation
🤖 Support Vector Machine (SVM)
- Model Training: An SVM model is trained on the training data.
- Evaluation: The model's performance is evaluated using accuracy score.

## Conclusion
🚀 This project demonstrates the use of a Support Vector Machine (SVM) to detect fraudulent credit card transactions. Proper preprocessing and encoding of the data are crucial steps in building an effective fraud detection model.
