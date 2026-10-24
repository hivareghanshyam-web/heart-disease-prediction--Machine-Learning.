# Heart Disease Prediction using Decision Tree

## Project Overview
This educational machine-learning project explores a heart-disease dataset and trains a Decision Tree classifier. It demonstrates data inspection, duplicate handling, train/test splitting, model training, classification metrics and hyperparameter tuning.

> **Medical disclaimer:** This is a learning project, not a clinically validated diagnostic system. Do not use it to make medical decisions.

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Jupyter Notebook.

## Repository Structure
```text
heart-disease-prediction-ml/
├── data/
│   └── README.md
├── notebooks/
│   └── heart_disease_prediction.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## Dataset Setup
The notebook expects a file named `heart (1).csv` in its working directory and references the source link included in the notebook. Before running it, download the dataset from that source if you have permission to use and redistribute it, then place the CSV in the notebook's working directory or update the file path. Check the dataset's licence/terms and credit the original source. Do not upload private or restricted health data.

## How to Run
1. Install Python 3.10+ and Jupyter Notebook, or open the notebook in Google Colab.
2. Install dependencies: `pip install -r requirements.txt`.
3. Download the permitted dataset and place it at the path expected by the notebook.
4. Open `notebooks/heart_disease_prediction.ipynb`.
5. Run cells in order and record the actual evaluation results.

## Workflow Covered
- Data overview and exploratory analysis
- Missing-value and duplicate checks
- Train/test split
- Decision Tree classification
- Accuracy, confusion matrix, precision, recall and classification report
- Decision Tree depth exploration and GridSearchCV

## Important Limitations / Future Work
- Validate the dataset source and document the exact licence/citation.
- Use a reproducible preprocessing pipeline and stratified splitting where appropriate.
- Compare with a baseline and other models using cross-validation.
- Report precision, recall, F1-score and confusion matrix, not accuracy alone.
- Audit possible data leakage and avoid clinical claims.
- Add a reproducible environment, saved model and optional demo only after validating the workflow.

## Author
Ghanshyam Hivare hivareghanshyam@gmail.com
Linkedin :-www.linkedin.com/in/ghanshyam-hivare45
