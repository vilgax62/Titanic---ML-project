# 🚢 Titanic - Machine Learning Project  

This project is based on the **Kaggle Titanic: Machine Learning from Disaster** competition.  
The goal is to predict passenger survival using machine learning techniques.  

---

## 📌 Project Overview  
- **Objective**: Predict whether a passenger survived the Titanic disaster.  
- **Dataset**: Titanic dataset from [Kaggle](https://www.kaggle.com/competitions/titanic/data).  
- **Model Used**: Logistic Regression.  
- **Best Kaggle Score**: **0.76555**.  

---

## ⚙️ Tech Stack  
- **Python** 🐍  
- **Pandas** – data manipulation  
- **NumPy** – numerical computing  
- **scikit-learn** – preprocessing, feature engineering, model training  

---

## 📂 Project Structure  
```
Titanic-ML-Project/
│── train.csv            # Training dataset
│── test.csv             # Test dataset
│── titanic_model.ipynb     # Python script for training & prediction
│── Submission.csv       # Final submission file
│── README.md            # Project documentation
```

---

## 🚀 Steps in the Project  
1. **Data Cleaning**  
   - Filled missing values (Age, Fare, Embarked).  
   - Dropped unnecessary columns (Cabin, Ticket, Name).  

2. **Feature Engineering**  
   - Encoded categorical features (`Sex`, `Embarked`).  
   - Applied scaling (StandardScaler & MinMaxScaler).  

3. **Model Training**  
   - Logistic Regression trained on processed dataset.  

4. **Prediction & Submission**  
   - Generated predictions on test dataset.  
   - Created submission file for Kaggle.  

---

## 📊 Result  
- Achieved **0.76555** Kaggle score.  
- Performance matches baseline Kaggle solutions.  

---

## 📝 How to Run  
1. Clone the repository:  
   ```bash
   git clone https://github.com/vilgax62/Titanic---ML-project
   cd Titanic-ML-Project
   ```  
2. Install dependencies:  
   ```bash
   pip install pandas numpy scikit-learn
   ```  
3. Run the script:  
   ```bash
   python titanic_model.py
   ```  
4. Submission file (`Submission.csv`) will be generated.  

---

## 🌟 Future Improvements  
- Try advanced models (Random Forest, XGBoost, LightGBM).  
- Perform hyperparameter tuning.  
- Add feature engineering (family size, title extraction, etc.).  

---

✉️ **Author**: *Nitesh Yadav*  
🎯 Open to opportunities in **Data Science / Machine Learning**.  
