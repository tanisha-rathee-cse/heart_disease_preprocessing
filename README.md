# Heart Disease Preprocessing

Data preprocessing for a heart disease prediction project. This notebook
prepares patient health data for machine learning by encoding categorical
features and scaling numerical features.

## Dataset
Heart Failure Prediction dataset from Kaggle (`heart.csv`).

| Feature | Description |
|---|---|
| Age, Sex | Patient details |
| ChestPainType | Type of chest pain (ATA, NAP, TA, ASY) |
| RestingBP | Resting blood pressure |
| Cholesterol | Serum cholesterol |
| FastingBS | Fasting blood sugar (0/1) |
| RestingECG | Resting ECG results |
| MaxHR | Maximum heart rate achieved |
| ExerciseAngina | Exercise-induced angina |
| Oldpeak | ST depression |
| ST_Slope | Slope of the peak exercise ST segment |
| HeartDisease | Target (0 = no, 1 = yes) |

## What's Done
- Loaded and explored the dataset
- One-hot encoding of categorical columns
- Feature scaling of numerical columns (Age, RestingBP, Cholesterol, MaxHR, Oldpeak) using StandardScaler

## Next Steps
- Train-test split
- Model training (Logistic Regression, KNN, etc.)
- Model evaluation

## Tech Stack
Python, NumPy, Pandas, Scikit-learn

## How to Run
1. Clone the repository:
   `git clone https://github.com/tanisha-rathee-cse/heart_disease_preprocessing.git`
2. Install the requirements:
   `pip install -r requirements.txt`
3. Open `heart_disease_preprocessing.ipynb` in Jupyter Notebook and run all cells.

## Author
Tanisha
