# 🚢 Titanic Survival Prediction  

<p align="center">
  <img src="https://en.wikipedia.org/wiki/Sinking_of_the_Titanic#/media/File:St%C3%B6wer_Titanic.jpg" alt="Titanic" width="600"/>
</p>

A machine learning project for the **Kaggle Titanic: Machine Learning from Disaster** competition.  
The goal is to predict whether a passenger survived the Titanic shipwreck, based on features such as age, sex, ticket class, and more.  

---

## 🏗️ Project Structure
```
├── titanic-comp-finale.ipynb   # Jupyter Notebook with full workflow  
├── data/                       # (optional) place Titanic CSV files here  
├── README.md                   # Project documentation  
```
---

## ✨ Features  

✅ **Exploratory Data Analysis (EDA):** Passenger demographics & survival insights  
✅ **Preprocessing:** Missing values, feature engineering, categorical encoding  
✅ **Models:** Logistic Regression, Random Forest, XGBoost (or others you used)  
✅ **Evaluation:** Accuracy, confusion matrix, cross-validation  
✅ **Submission:** Generates `submission.csv` for Kaggle  

---

## 🛠️ Requirements  

- python 3.8+  
- jupyter  
- numpy  
- pandas  
- matplotlib  
- seaborn  
- scikit-learn  
- xgboost  

Install dependencies with:  

pip install -r requirements.txt  

---

## 🚀 Usage  

1. Clone the repository:  
   git clone https://github.com/ViRuS79Pro/titanic-analysis.git  
   cd titanic-survival  

2. Download Titanic dataset from Kaggle and place inside `data/`:  
   https://www.kaggle.com/c/titanic/data  

3. Run the notebook:  
   jupyter notebook titanic-comp-finale.ipynb  

4. Generate predictions → outputs `submission.csv` for Kaggle.  

---


## 🔮 Future Work  

- Hyperparameter tuning with Optuna/GridSearch  
- Advanced feature engineering  
- Stacking/ensemble models  
- Deploy as a **Streamlit/Flask** web app  

---

## 📜 License  

This project is open-source under the **MIT License**.  

---

<p align="center">Made with ❤️ and ML 🚀</p>
