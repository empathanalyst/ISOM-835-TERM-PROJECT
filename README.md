# ISOM-835-TERM-PROJECT
Forecasting Diabetes Onset: A Predictive Analytics Study on the 2015 CDC BRFSS Health Indicators Dataset




Project Summary  
This project applies predictive analytics to forecast the onset of diabetes using the 2015 CDC BRFSS Health Indicators dataset. It leverages machine learning models to identify key behavioral and demographic risk factors contributing to diabetes in the U.S. population.


Project Objectives  
- Build classification models to predict diabetes status: No Diabetes (0), Pre-Diabetes (1), and Diabetes (2).  
- Use SMOTE to address class imbalance.  
- Compare multiple supervised ML algorithms (Logistic Regression, Random Forest, XGBoost).  
- Evaluate model performance using F1-score, ROC-AUC, and accuracy.  
- Deliver actionable insights through feature importance analysis and visualizations.



 Dataset Description  
- Source: [CDC BRFSS 2015 Dataset](https://www.cdc.gov/brfss/annual_data/annual_2015.html)
- kaggle: https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset
- Size: ~250,000 records  
- Features: Age, BMI, activity levels, alcohol use, smoking status, general health, and more  
- Target Variable: `Diabetes_012`  
  - 0: No Diabetes  
  - 1: Pre-Diabetes  
  - 2: Diabetes  



Tools & Libraries Used  
- Platform: Google Colab (Python)  
- Key Libraries:
  - `pandas`, `numpy` – data processing  
  - `matplotlib`, `seaborn` – visualization  
  - `scikit-learn` – machine learning  
  - `xgboost` – gradient boosting  
  - `imblearn` – SMOTE for class imbalance  



How to Run  
1. Click the link below to open the Colab notebook.  
2. Click `Runtime > Run all` to execute all cells.  
3. Make sure your Colab runtime has internet access.  
4. View outputs inline including charts and evaluation metrics.



Google Colab Notebook  
- [Full Notebook: Data Cleaning, Modeling, Evaluation](https://colab.research.google.com/drive/1ABaf4IeLBt2kVc8Cq-Ac6GaByZCdyFPf?usp=sharing)


Final Report :
https://github.com/empathanalyst/ISOM-835-TERM-PROJECT/blob/main/Finalreport.pdf



 Visualizations  
https://github.com/empathanalyst/ISOM-835-TERM-PROJECT/tree/main/visualizations



###  .gitignore  
The repo includes a `.gitignore` to exclude checkpoints, pycache, and unnecessary system files.



### 🙋‍♀️ About Me  
Hi! I’m Anushka, a Master’s student in Business Analytics with a clinical background in physiotherapy. This project reflects my interest in healthcare analytics, machine learning, and digital health innovation.  
Let’s connect on [LinkedIn](https://www.linkedin.com/in/your-link) 🚀


