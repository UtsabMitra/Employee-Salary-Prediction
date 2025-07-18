
---

## 📊 Dataset

- **Source:** [UCI Machine Learning Repository - Adult Dataset](https://archive.ics.uci.edu/ml/datasets/adult)
- **Description:** Contains census data including age, education, occupation, marital status, etc., with income class labels.

---

## 🔧 Libraries Used

- `pandas` – Data loading and manipulation  
- `matplotlib` – Visualizations (boxplot for outlier detection, bar chart for model comparison)  
- `scikit-learn` – Preprocessing, model training, and evaluation  
- `joblib` – Saving and loading the trained model  
- `streamlit` – Web application interface  

---

## 🚀 Model Building Process

1. **Data Preprocessing:**  
   - Handled categorical variables using `LabelEncoder`  
   - Visualized outliers using boxplots  
   - Normalized features using `StandardScaler`  

2. **Model Training and Evaluation:**  
   - Trained multiple models: Logistic Regression, Random Forest, SVM, KNN, and Gradient Boosting  
   - Used `accuracy_score` and `classification_report` to evaluate models  
   - Selected and saved the best-performing model using `joblib`  

3. **Deployment:**  
   - Built an interactive Streamlit web app  
   - Supports both single-entry prediction and batch prediction via CSV upload  

---

## 🖥️ Running the Application

1. **Install required packages:**

```bash
pip install -r requirements.txt
