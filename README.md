
# Employee Performance Prediction

## Overview
This project analyzes employee performance data at **INX Future Inc.**, aiming to identify key drivers of productivity and develop a predictive model for future hiring. With declining client satisfaction and rising service escalations, the focus is on **data-driven talent management** to enhance employee engagement and organizational success.

### Key Objectives
- Analyze department-wise performance trends  
- Identify top 3 factors influencing performance  
- Build a predictive model to forecast employee output  
- Provide actionable HR recommendations

## Domain Analysis
Employee performance depends on factors like demographics, job roles, compensation, and work-life balance. Department-level insights help uncover inefficiencies and potential for targeted interventions.

### Influential Feature Categories:
- **Demographics**: Age, Gender, Marital Status, Education Background  
- **Job Info**: Department, Role, Travel Frequency, Distance from Home  
- **Compensation**: Hourly Rate, Salary Hike %, Job Satisfaction  
- **Experience**: Total Work Experience, Tenure, Promotions, Manager Tenure  
- **Engagement**: Job Involvement, Environment & Relationship Satisfaction, Overtime  
- **Performance**: Ratings, Attrition, Training Frequency

## Business Case
- **Goal**: Reverse 8% client satisfaction drop by optimizing HR decisions  
- **Benefits**:
  - Smarter hiring and training  
  - Lower attrition and better retention  
  - Data-backed insights for leadership  
  - Sustain INX’s “Best Employer” status

## Installation
```bash
git clone https://github.com/your-repo/employee-performance.git
cd employee-performance
pip install -r requirements.txt
```

## Requirements
```
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
```

## Usage
```bash
# Train model
python train_model.py
```
Evaluate using classification metrics (accuracy, F1-score, ROC-AUC).

## Results
- **Top Features**: Job Involvement, Environment Satisfaction, Years in Role  
- **Best Model**: XGBoost (outperformed Logistic Regression, SVM, KNN, RF)  
- **Impact**: Enables predictive hiring and performance-driven workforce planning

## Contributing
Open to collaboration and improvements via pull requests or issues.
