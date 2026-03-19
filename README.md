#  Digital Addiction Detection

> Can AI detect if you're addicted to your phone? This project builds a machine learning model to automatically detect digital addiction from smartphone behavioral data.

##  Overview
Built a complete end-to-end ML pipeline on 50,000 smartphone users to predict digital addiction using objective behavioral signals like phone usage hours, sleep patterns, stress levels, and social media consumption. Applied SHAP explainable AI to understand WHY the model makes each prediction.

##  Results

| Model | Accuracy |
|---|---|
| Logistic Regression | 88.82% |
| Random Forest | 99.39% |
| Gradient Boosting | 99.48% |

##  Key Findings
- **Screen-to-Sleep Ratio** is the #1 predictor of digital addiction
- **Stress Level** and **Daily Phone Hours** are 2nd and 3rd most important
- **Age, Gender, Device Type** have almost zero impact — addiction is behavioral not demographic

##  Tech Stack
```
Python | Scikit-learn | XGBoost | SHAP | Pandas | NumPy | Matplotlib | Seaborn | Google Colab
```

##  Project Structure
```
Digital-Addiction-Detection/
├── Digital_Addiction_Detection_Model.ipynb  ← Complete ML pipeline
├── Smartphone_Usage_Productivity_Dataset_50000.csv  ← Raw dataset
├── preprocessed_dataset.csv  ← Engineered dataset with labels
└── README.md
```

## Pipeline
```
Raw Data → Label Engineering → Feature Engineering → Model Training → SHAP Explainability
```

##  SHAP Feature Importance
Top predictors identified by SHAP analysis:
1. Screen-to-Sleep Ratio
2. Stress Level
3. Daily Phone Hours
4. Sleep Hours
5. Social Media Hours

##  How to Run
1. Open `Digital_Addiction_Detection_Model.ipynb` in Google Colab
2. Upload the dataset CSV when prompted
3. Run all cells in order

## 👤 Author
**Bobby Balyan**
B.Tech CSE (AI & ML) — CT Group of Institutions(CTIEMT)

GitHub: [@aimlwithbobbybalyan](https://github.com/aimlwithbobbybalyan)

Email: bobby.2301385@stu.ctgroup.in
