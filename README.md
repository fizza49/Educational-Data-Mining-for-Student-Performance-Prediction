# Educational-Data-Mining-for-Student-Performance-Prediction


## Objective

To predict student performance (GPA and grade class) using academic, behavioral, and demographic data by applying regression and classification models. The project aims to help identify at-risk students and enable early intervention strategies using data-driven insights.

## Dataset Overview

#### Source: [kaggle](http://kaggle.com/datasets/rabieelkharoua/students-performance-dataset)

#### Size: 
2,392 records, 15 features

#### Target Variables:
GPA (continuous), GradeClass (categorical)

#### Feature Categories:

- Demographic: Age, Gender, Ethnicity

- Academic: Study Time, Absences, Grades

- Behavioral: Tutoring, Parental Support, Extracurricular Activities

## Tools & Technologies

#### Language:
Python

#### Libraries:
Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib, XGBoost

#### Visualization: 
Power BI

#### Modeling Techniques:

Regression: Linear, Decision Tree, Random Forest, KNN, Voting, and Stacking

Classification: Random Forest, XGBoost

## Data Pipeline

#### Data Cleaning:
Removed duplicates, invalid age/GPA, standardized types

#### Feature Engineering: 
Created new metrics like StudyEfficiency, AttendanceRate

#### Transformation: 
One-hot encoding, binning, and outlier treatment

#### EDA: Statistical summaries, correlations, and interactive visualizations

### Modeling:

Regression for GPA prediction

Classification for grade classification

### Evaluation:

Regression: MAE, MSE, RMSE, R²

Classification: Accuracy, Precision, Recall, F1-score

## Key Results

Best Regression Model – Stacking Regressor
R² Score: 0.9705

MAE: 0.0243

RMSE: 0.1562

Best Classification Model – XGBoost
Accuracy: 91.78%

F1-score: 0.8606

## Insights & Impact

- Higher Study Time & Parental Support → Higher GPA

- Extracurricular Activities showed mixed influence

- Grade class imbalance requires model balancing techniques

Power BI Dashboard: Used to visualize student performance trends, parental influence, and attendance impact.

 ## Future Improvements
 
- Incorporate k-fold cross-validation
- Apply class balancing (e.g., SMOTE)
- Perform hyperparameter tuning
- Add model interpretability tools (e.g., SHAP)
- Explore real-time pipelines with Streamlit or Flask
  
## Getting Started

### Prerequisites

- Python installed version 3.12 or above
- Python IDE (Visual Studio Code, Pycharm etc)
- Google Colab
- To run this project, you need to install streamlit pyngrok. It can be installed using pip:

``` C
pip install -q streamlit pyngrok
```

### How to run?

-clone the repository
git clone [https://github.com/yourusername/student-performance-prediction](https://github.com/fizza49/Educational-Data-Mining-for-Student-Performance-Prediction.git)


 ## Contributors
 [Fizza Kashif](https://github.com/fizza49)
 [Hareem Fatima](https://github.com/HareemFatima5)
 [Misbah Shaheen](https://github.com/Misbah-shaheen)
 [Sana Khan Khitran](https://github.com/sanakhitran22)
