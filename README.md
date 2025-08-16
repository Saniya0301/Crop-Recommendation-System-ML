# 🌱 Crop Recommendation System using Machine Learning

## 📌 Overview  
This project predicts the **best crop to grow** based on soil and climate conditions using **Machine Learning**.  
The model is trained on the `Crop_recommendation.csv` dataset which contains 2200 samples and 22 different crop labels.  

We used multiple ML algorithms and found that **Random Forest Classifier** gave the best accuracy (~99.3%).  

---

## 📊 Dataset  
- **Rows:** 2200  
- **Columns:** 8  
- **Features:**  
  - `N` → Nitrogen content in soil  
  - `P` → Phosphorus content in soil  
  - `K` → Potassium content in soil  
  - `temperature` → Temperature in °C  
  - `humidity` → Relative Humidity in %  
  - `ph` → pH value of soil  
  - `rainfall` → Rainfall in mm  
- **Label:** `crop` (22 different crop types)  

---

## ⚙️ Technologies Used  
- Python 3.8+  
- Pandas, NumPy  
- Scikit-learn  
- Seaborn & Matplotlib (visualization)  
- Pickle (for saving models)  

---

## 🚀 Model Training  
1. **Data Preprocessing**  
   - Handled missing values and duplicates  
   - Label encoded crop types  
   - Applied **MinMaxScaler** and **StandardScaler**  
2. **Model Comparison**  
   - Logistic Regression, SVM, Naive Bayes, KNN, Decision Trees, Random Forest, Bagging, Gradient Boosting, AdaBoost  
   - Best accuracy: **Random Forest (99.3%)**  
3. **Model Saving**  
   - Trained model saved using `pickle`  

---

📌 Future Improvements

Deploy model with Flask/Django/Streamlit

Add a frontend for user interaction

Use deep learning for better prediction

Collect real-time soil & weather data

----

🙌 Acknowledgements

Dataset: Kaggle - Crop Recommendation Dataset

ML Algorithms implemented with Scikit-learn

---
Author

SANIYA CHHABRA

## 📂 Project Structure  

