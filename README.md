# 🏡 House Price Prediction using Machine Learning

## 🔍 Objective
The goal of this project is to build a machine learning model capable of predicting house sale prices based on features like construction quality, living area, number of rooms, garage size, and more.

---

## 🛠 Tools & Technologies Used
- Python
- Pandas, NumPy
- Scikit-Learn
- Matplotlib, Seaborn

---

## 📂 Project Workflow

### 1️⃣ Data Exploration
- Loaded dataset and analyzed structure
- Identified missing values and duplicates
- Visualized correlations using a heatmap

### 2️⃣ Data Cleaning & Preprocessing
✔ Handled missing values using forward fill  
✔ Removed irrelevant features  
✔ Detected and treated outliers using IQR method  
✔ Converted categorical values using Label Encoding  
✔ Scaled numerical values using **StandardScaler**

### 3️⃣ Feature Engineering
- Checked target distribution (SalePrice)
- Identified skew and scaling impact

### 4️⃣ Model Training
Algorithm used: **Linear Regression**

Train–Test Split: `80% train / 20% test`

### 5️⃣ Model Evaluation
| Metric | Score |
|--------|--------|
| R² Score | **0.913** |
| MAE | **~16297** |
| RMSE | **~20372** |

---

## 🧠 Key Findings
- House quality score (`OverallQual`) and total living area (`GrLivArea`) are the strongest predictors.
- Garage size, year built, and total basement area also significantly impact price.
- Linear Regression produced strong performance with high R² value.

---

## 🚧 Challenges Faced
- Many categorical variables required encoding
- Data contained substantial outliers
- Ensuring proper scaling without data leakage

---

## 📎 Files Included
| File | Description |
|------|------------|
| `supervised_learning_project.ipynb` | Notebook with full ML workflow |
| `README.md` | Project documentation |

---

## 🚀 Future Enhancements
- Test advanced models (Random Forest, XGBoost, Gradient Boosting)
- Hyperparameter tuning
- Create a Streamlit web app for prediction
