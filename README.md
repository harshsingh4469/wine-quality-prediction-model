
🍷 Wine Quality Prediction using Machine Learning
📌 Overview

This project focuses on predicting the quality of red wine using machine learning techniques. By analyzing physicochemical properties of wine, the model classifies wine quality and helps in understanding key influencing factors.

The project demonstrates data preprocessing, exploratory data analysis (EDA), model building, and evaluation using Python.

📂 Dataset

The dataset used is the Wine Quality Dataset, containing 1599 samples and 12 features, including:

Fixed Acidity
Volatile Acidity
Citric Acid
Residual Sugar
Chlorides
Free Sulfur Dioxide
Total Sulfur Dioxide
Density
pH
Sulphates
Alcohol
Quality (Target Variable)

📌 No missing values were found in the dataset

⚙️ Tech Stack
Programming Language: Python
Libraries Used:
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
🔍 Project Workflow
1. Data Collection
Loaded dataset using Pandas
Checked dataset shape and structure
2. Data Preprocessing
Verified missing values (none found)
Feature-target separation
3. Exploratory Data Analysis (EDA)
Distribution of wine quality
Relationship between features like:
Volatile acidity vs Quality
Citric acid vs Quality
Statistical summary using .describe()
4. Model Building
Split dataset into training and testing sets
Used Random Forest Classifier for prediction
5. Model Evaluation
Evaluated model using accuracy score
🤖 Machine Learning Model
Algorithm: Random Forest Classifier
Why Random Forest?
Handles non-linearity well
Reduces overfitting
Works effectively on tabular datasets
📊 Results
Achieved good accuracy in predicting wine quality
Identified important features influencing wine quality such as:
Alcohol
Volatile Acidity
Sulphates
🚀 How to Run the Project
# Clone the repository
git clone https://github.com/your-username/wine-quality-prediction.git

# Navigate to project folder
cd wine-quality-prediction

# Install dependencies
pip install -r requirements.txt

# Run the notebook / script
📈 Future Improvements
Hyperparameter tuning for better accuracy
Try advanced models like:
XGBoost
LightGBM
Deploy model using Flask / Streamlit
Build interactive dashboard
📌 Key Learnings
End-to-end ML pipeline implementation
Data visualization and insights extraction
Feature importance analysis
Model evaluation techniques
🤝 Contributing

Contributions are welcome! Feel free to fork the repo and submit a pull request.

📬 Contact

For any queries or collaboration:

Name: Harsh Singh
Email: harshsingh@4469.com
LinkedIn: https://www.linkedin.com/in/harsh-singh-a7b490255
