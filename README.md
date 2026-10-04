# Student Performance Predictor

A machine-learning portfolio project built with Python, scikit-learn, pandas, and Streamlit.

## What it does
The app predicts a student's final score from:
- Attendance percentage
- Study hours per day
- Previous score
- Sleep hours
- Assignments completed

## Tech stack
- Python
- pandas
- scikit-learn
- Streamlit

## Run locally

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Model
Random Forest Regressor trained on a synthetic educational dataset for demonstration purposes.

Current test result on the included dataset:
- MAE: about 5.37 points
- R²: about 0.735

## Resume line
Built a Streamlit-based machine-learning application that predicts student academic performance using attendance, study habits, previous scores, sleep, and assignment completion, using a Random Forest regression model in scikit-learn.

> Educational demo only. The dataset is synthetic and this app should not be used for real academic decisions.
