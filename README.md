🌱 Organic Farming Suitability Prediction Using Machine Learning

📌 Project Overview

This project uses Machine Learning classification algorithms to predict whether agricultural land is suitable or not suitable for organic farming.

The model analyzes agricultural, soil-related, and farming parameters to classify land into two categories:

- Suitable: Conditions are suitable for organic farming.
- Not Suitable: Conditions are not suitable for organic farming.

The main objective is to explore how Machine Learning can support agricultural data analysis and organic farming suitability prediction.

🎯 Project Objectives

- Analyze agricultural and soil-related data.
- Perform data cleaning and preprocessing.
- Explore patterns and relationships using data visualization.
- Train multiple Machine Learning classification models.
- Compare model performance using cross-validation.
- Select the best-performing model.
- Evaluate the final model and save it for future use.

🛠️ Technologies and Libraries Used

Programming Language: Python

Tools:

- Jupyter Notebook

Python Libraries:

- NumPy – Numerical computations.
- Pandas – Data manipulation and analysis.
- Matplotlib – Data visualization.
- Seaborn – Statistical visualization.
- Scikit-learn – Machine Learning algorithms and evaluation.
- Joblib – Saving the trained model.

🤖 Machine Learning Algorithms

Four classification algorithms are implemented in this project:

1. Logistic Regression
2. Decision Tree Classifier
3. K-Nearest Neighbors (KNN)
4. Random Forest Classifier

The models are compared using 5-Fold Stratified Cross-Validation. The model with the highest weighted F1-score is selected as the best model.

🔍 Project Workflow

1. Import required Python libraries.
2. Load the agricultural dataset.
3. Explore dataset information and statistical summaries.
4. Clean column names and handle missing values.
5. Check and remove duplicate records.
6. Handle infinite values.
7. Perform Exploratory Data Analysis (EDA).
8. Visualize numerical and categorical features.
9. Analyze target class distribution.
10. Separate input features and target labels.
11. Split the dataset into 80% training and 20% testing data.
12. Apply preprocessing techniques:
    - Median imputation for numerical features.
    - Most frequent imputation for categorical features.
    - Standard scaling.
    - One-Hot Encoding.
13. Train four classification algorithms.
14. Compare models using 5-Fold Cross-Validation.
15. Select the best-performing model.
16. Evaluate the selected model using test data.
17. Save the final trained model using Joblib.

📊 Model Evaluation

The project uses the following evaluation metrics:

- Accuracy
- Balanced Accuracy
- Weighted Precision
- Weighted Recall
- Weighted F1-Score
- Matthews Correlation Coefficient (MCC)
- ROC-AUC Score

Visualizations include:

- Class Distribution Charts
- Histograms
- Box Plots
- Correlation Heatmap
- Model Performance Comparison
- Confusion Matrix
- ROC Curve
- Feature Importance

📁 Project Structure

Organic-Farming-Suitability-Prediction/
│
├── Organic-Farming-Suitability-Prediction.ipynb
│
└── README.md

⚙️ Installation and Setup

1. Clone the Repository

git clone https://github.com/YOUR-USERNAME/Organic-Farming-Suitability-Prediction.git

Replace "YOUR-USERNAME" with your GitHub username.

2. Open the Project Folder

cd Organic-Farming-Suitability-Prediction

3. Install Required Libraries

pip install numpy pandas matplotlib seaborn scikit-learn joblib jupyter

4. Add the Dataset

The notebook requires the following CSV dataset:

"organic_farming_suitability_1000_source_calibrated.csv"

Place the dataset in your project folder and update the "DATA_PATH" variable in the notebook to:

DATA_PATH = "organic_farming_suitability_1000_source_calibrated.csv"

5. Run the Jupyter Notebook

jupyter notebook

Open "Organic-Farming-Suitability-Prediction.ipynb" and execute the cells sequentially.

💾 Trained Model

After successful execution, the notebook automatically saves the best-performing trained model as:

"organic_farming_best_model.joblib"

The exported file contains the trained model, selected model name, feature columns and dataset information.

👨‍💻 Author

Name: SUPRIYA PAL 

GitHub: https://github.com/sp5258p

---

⭐ If you find this project interesting, feel free to star this repository!

Project Domain: Machine Learning | Python | Data Science | Agriculture
