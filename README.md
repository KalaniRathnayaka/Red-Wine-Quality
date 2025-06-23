# Red-Wine-Quality

🍷 Wine Quality Prediction & Data Mining Project
🎯 Objective
This project applies regression and data mining techniques on the Wine Quality Dataset to:

Predict the quality of red wine based on physicochemical tests.

Evaluate model performance using standard metrics.

Visualize and interpret model results.

📁 Dataset
Source: Wine Quality Dataset on Kaggle

File Used: winequality-red.csv

Attributes:

11 numeric input variables (e.g., acidity, sugar, alcohol)

1 target variable: quality (integer score between 3 and 8)

🧰 Technologies Used
Python

Pandas

Scikit-learn

Seaborn & Matplotlib

🚀 How to Run
Clone the repo or open the notebook in Google Colab / Jupyter.

Download the dataset (winequality-red.csv) from Kaggle.

Place the CSV in the notebook's working directory.

Run each code cell sequentially.

🔍 Project Steps
1. Data Loading and Cleaning
The dataset is loaded with pd.read_csv()

Column names are cleaned and standardized

2. Feature and Target Preparation
Input features: all columns except quality

Target: quality

3. Linear Regression Model
Dataset split into training and test sets

Linear regression model trained and evaluated

Metrics: Mean Squared Error, R² Score

Coefficients printed for each feature

4. Visualization
Scatterplot of actual vs predicted wine quality

📈 Sample Output
yaml
Copy
Edit
📉 Mean Squared Error: 0.40
📈 R² Score: 0.33

📊 Feature Coefficients:
fixed acidity: 0.02
volatile acidity: -1.08
...
alcohol: 0.27
📦 Files Included
winequality-red.csv (not included, download from Kaggle)

wine_quality_regression.ipynb (main notebook)

README.md

💡 Future Improvements
Try RandomForest or XGBoost regressors

Apply KMeans clustering

Use Apriori to discover association rules

Build a Streamlit dashboard for deployment

👨‍🏫 Ideal For:
Data science learners

Machine learning practicals

Academic mini-projects

