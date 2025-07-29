# Churn-Prediction-Model


## Overview
This project focuses on predicting customer churn using a structured machine learning approach. Built using Python and executed in Google Colab, the model aims to identify customers likely to discontinue services, enabling the business to proactively improve retention.

## Objectives
- Predict customer churn using Logistic Regression.
- Interpret key factors contributing to churn.
- Quantify the potential business impact of predictive churn modeling.

## Dataset
- **Source**: Telco Customer Churn Dataset
- **Size**: 7,043 entries
- **Features**: Demographics, service subscriptions, billing behavior, payment method, contract type, etc.
- **Target**: `Churn` (Boolean)

## Methodology
1. **Exploratory Data Analysis (EDA)**
   - Monthly Charges vs Churn
   - Tenure vs Churn
   - Churn Rate by Contract Type

2. **Preprocessing**
   - Null handling, encoding, scaling
   - SMOTE for handling class imbalance
   - Train-test split (80/20)

3. **Modeling**
   - Logistic Regression (primary model)
   - Random Forest (benchmark)
   - Metrics evaluated: Accuracy, Precision, Recall, F1-score, Confusion Matrix, ROC Curve

4. **Evaluation Metrics**
   - **Logistic Regression**
     - Accuracy: 81%
     - Precision (Churn): 63%
     - Recall (Churn): 64%
     - F1-score (Churn): 64%
   - **Random Forest**
     - Accuracy: 79%
     - Precision (Churn): 61%
     - Recall (Churn): 57%
     - F1-score (Churn): 59%

5. **Feature Insights**
   - Top drivers of churn include low tenure, month-to-month contracts, high monthly charges, and electronic check payments.

## Business Impact (Estimation)
- Average value of a retained customer: ₹6,000
- True churners correctly predicted: 240
- Estimated revenue retained: ₹14,40,000
- Cost from false positives: ₹70,000
- **Net revenue impact**: ₹13,70,000

## Deliverables
## Deliverables
- 📄 [Churn_Prediction_Report.docx](./Churn_Prediction_Report.docx): Detailed project report  
- 📊 [Churn_Prediction_Presentation.pptx](./Churn_Prediction_Presentation.pptx): Executive summary presentation  
- 🧾 [Churn_Prediction_Notebook.ipynb](https://colab.research.google.com/drive/1AI18-GCkazuVSSUwYmUNPhbYmpYUtQTK?usp=sharing): Complete Jupyter Notebook (hosted on Colab)

## Future Work
- Tune thresholds and try ensemble models (XGBoost, LightGBM)
- Add SHAP or LIME for interpretability
- Build a real-time dashboard using Streamlit or Power BI

## Tools Used
- Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, SMOTE, Google Colab

---

**Author**: [Rishav Vashisht]  

