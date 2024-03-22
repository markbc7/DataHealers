<h1 align="center">Effective Prediction of Chronic Diseases with Explainable AI</h1>

<p align="center">
  <strong>Team: DAtA healers (Group 18)</strong>
</p>

<p align="center">
  <a href="#project-overview">Overview</a> •
  <a href="#repository-structure">Repository</a> •
  <a href="#datasets">Datasets</a> •
  <a href="#approach">Approach</a> •
  <a href="#results--insights">Results</a> •
  <a href="#conclusion">Conclusion</a> •
  <a href="#contact-information">Contact</a>
</p>

---

## 👥 Team Members
- Daniyal Asif
- Adithya Shetty
- Anwar Shamim
- Kristian Kuznetsov (Mentor)

## 🔍 Project Overview
This project aims to leverage machine learning (ML) and explainable artificial intelligence (XAI) techniques to predict chronic diseases, specifically focusing on Kidney, Liver, and Heart Diseases. Our goal is to not only accurately predict these conditions but also provide interpretable and transparent model predictions to enhance trust and usability in healthcare settings.

## 📂 Repository Structure
- `data`: Folder contains datasets used in the project.
- `Final_report.pdf`: Detailed report of our findings and methodology.
- `PROJECT-CHD_1.ipynb`: Jupyter notebook for Chronic Heart Disease prediction analysis.
- `PROJECT-CKD_1.ipynb`: Jupyter notebook for Chronic Kidney Disease prediction analysis.
- `PROJECT-CLD_1.ipynb`: Jupyter notebook for Chronic Liver Disease prediction analysis.
- `requirements.txt`: List of Python dependencies for reproducing the analysis.

## 📊 Datasets
We worked with three distinct datasets for our project:
- **Kidney Disease Dataset**: Consisting of 400 observations with 26 features.
- **Liver Disease Dataset**: Encompassing 30,690 observations and 10 features.
- **Heart Disease Dataset**: Comprising 70,000 observations with 13 features.

## 🚀 Approach
Our methodology involved several stages, tailored to each disease, focusing on preprocessing, feature selection, and the application of various machine learning and explainable AI techniques.

### 🧹 Preprocessing
- **Data Encoding**: Converting categorical data into a machine-readable form.
- **Missing Value Imputation**: Employing iterative imputation methods to handle missing data.
- **Data Scaling**: Utilizing Robust Scaling, Standard Scaling, and Min-Max scaling to normalize feature scales.
- **Data Cleaning**: Addressing issues in the datasets to prepare them for analysis.
- **Data Balancing**: Using techniques like SMOTE for balancing imbalanced datasets.

### 🎯 Feature Selection
Identifying and selecting the most informative features through methods like Mutual Information Score to improve model performance.

### 🤖 Machine Learning Models
We applied a variety of machine and ensemble learning models to predict disease presence, evaluating their performance through accuracy, precision, recall, F1-score, and ROC-AUC metrics. 

<p align="center"> <img src="https://i.imgur.com/EUVjyv0.png" alt="CKD" width="800"> <br> <em>Chronic Kidney Disease Model Performance</em> </p>
<p align="center"> <img src="https://i.imgur.com/zeJCUgu.png" alt="CLD" width="800"> <br> <em>Chronic Liver Disease Model Performance</em> </p>
<p align="center"> <img src="https://i.imgur.com/HqXzUU4.png" alt="CHD" width="800"> <br> <em>Chronic Heart Disease Model Performance</em> </p>


## 🔍 Explainable AI (XAI)
To address the "black box" nature of traditional ML models, we incorporated XAI techniques, including LIME (Local Interpretable Model-Agnostic Explanations) and SHAP (Shapley Additive Explanations), to provide insights into how model predictions are made, thereby enhancing the interpretability and transparency of our models.

## 📈 Results & Insights

<p align="center"> <img src="https://i.imgur.com/QWYJJO8.png" alt="LIME" width="800"> <br> <em>LIME Explanations</em> </p>
<p align="center"> <img src="https://i.imgur.com/hrLEVJ9.png" alt="SHAP1" width="800"> <br> <em>SHAP Summary</em> </p>
<p align="center"> <img src="https://i.imgur.com/TvDGJUN.png" alt="SHAP" width="800"> <br> <em>SHAP Feature Impact</em> </p>

Our models achieved high performance across all diseases, with key insights revealing the significance of various features in predicting each condition. For instance, features like Hypertension and Diabetes Mellitus were crucial in predicting Kidney Disease, while Direct Bilirubin and Total Bilirubin were significant for Liver Disease predictions.

## 🎉 Conclusion
By applying ML techniques and integrating XAI, we effectively predicted chronic diseases and provided interpretable insights into the models' predictions. This project not only showcases the application of learned ML techniques but also highlights the importance of explainability and interpretability in healthcare AI solutions.

## 📧 Contact Information
For more details, you can reach out to us:
- Daniyal Asif: Daniyal.Asif@skoltech.ru
- Adithya Shetty: Adithya.Shetty@skoltech.ru
- Anwar Shamim: Anwar.Shamim@skoltech.ru
