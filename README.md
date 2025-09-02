> **Disclaimer:** This project was developed as part of a **University of Liverpool** assignment.  
> It is for **educational purposes only** and **must not be copied, reused, or distributed** without permission, in accordance with the University's academic integrity policies.
>
> # Student Grade Prediction (ML Pipeline)

A Jupyter Notebook project that explores and models a tabular dataset to **predict student grades**.  
It includes **EDA**, **feature encoding**, **train/test splitting**, **scaling**, and multiple **baseline & tree-based models**, with clear visualisations and metrics.

## What it does
- **Data loading** from `assign1-grades.csv`
- **EDA & Visualisation**: histograms, correlation heatmaps vs **Grade**
- **Preprocessing**:
  - Convert categorical features to numeric (category codes)
  - Train/test split (80/20), `random_state=42`
  - `StandardScaler` via a `Pipeline`
- **Models tried**:
  - Linear Regression (baseline)
  - Decision Trees / Random Forests
  - (KNN and Logistic Regression explored)
- **Evaluation**:
  - Predictions on the test set
  - Error metrics (e.g., MSE/RMSE)
  - Confusion matrix visualisation (when treating as classification)

## Files
- `final_code.ipynb` — main notebook with EDA → preprocessing → modelling
- `assign1-grades.csv` — input dataset (expected in the project root)

## How to Run
1. **Clone or download the project**  
   ```bash
   git clone https://github.com/your-username/student-grade-prediction.git
   cd student-grade-prediction
