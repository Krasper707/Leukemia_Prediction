# Leukemia Prediction using Machine Learning

## 📌 Project Overview
This project aims to predict the likelihood of leukemia in patients using machine learning techniques. By leveraging data from Kaggle, we performed feature engineering, data visualization, and applied machine learning models to classify leukemia status with an accuracy of 85%.

## 📂 Dataset
- **Source:** Kaggle 
- **Key Features:**
  - Gender
  - White Blood Cell (WBC) Count
  - Infection_History     
  - Red Blood Cell (RBC) Count
  - Alcohol_Consumption   
  - Platelet Count
  - Family History
  - Leukemia Status (Target Variable)

## 🔬 Exploratory Data Analysis (EDA)
Several visualizations were performed to analyze the dataset:
- **Leukemia status based on gender** 📊
- **WBC vs Leukemia Status** 📈
- **RBC vs Leukemia Status** 📉
- **Platelet Count vs Leukemia Status** 📊
- **Leukemia Status based on Family History** 🏠

## 🛠️ Data Preprocessing & Feature Engineering
- Handled missing values and outliers
- Used **Synthetic Minority Over-sampling Technique (SMOTE)** to balance the dataset
- Feature scaling and encoding applied where necessary

## 🤖 Machine Learning Models Used
1. **Decision Tree Classifier**
2. **Random Forest Classifier**

### 🎯 Model Performance
- Achieved an **accuracy of 85%**

## 📌 Installation & Usage
### Prerequisites
Ensure you have Python installed along with the required libraries:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
```

### Running the Project
1. Clone the repository:
```bash
git clone https://github.com/your-username/leukemia-prediction.git
```
2. Navigate to the project directory:
```bash
cd leukemia-prediction
```
3. Run the Jupyter Notebook or Python script:
```bash
jupyter notebook leukemia_prediction.ipynb
```

## 📊 Results & Insights
- WBC and RBC counts showed strong correlation with leukemia status.
- Patients with a family history of leukemia had a significantly higher likelihood of being diagnosed.
- SMOTE improved model performance on imbalanced data.

## 📜 Future Enhancements
- Experiment with **other ML models** (XGBoost, SVM, Neural Networks)
- Feature selection for improving accuracy
- Deploying as a web app for real-world usage

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
