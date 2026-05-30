# Heart Disease EDA & Risk Factor Analysis

## Project Overview
An Exploratory Data Analysis (EDA) project aimed at identifying key clinical risk factors for heart disease. By analyzing a dataset of 1,025 patient records, this project uses statistical distributions, correlation matrices, and data visualization to uncover the most significant predictors of cardiovascular illness.

## Tech Stack
* **Language:** Python 3
* **Environment:** Jupyter Notebook
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn

## Key Insights Discovered
* **Age & Diagnosis:** Heart disease diagnoses in this dataset peak significantly among patients aged 50–60.
* **Chest Pain (cp):** Asymptomatic and non-typical angina (types 1, 2, and 3) are drastically stronger indicators of heart disease compared to typical angina.
* **Maximum Heart Rate (thalach):** Counter-intuitively, patients diagnosed with heart disease exhibited a higher median maximum heart rate during stress testing than healthy patients.
* **Data Integrity:** The dataset was robust with 0 null values, requiring minimal imputation and allowing for high-confidence visualizations.

## Repository Structure
* `heart_disease_analysis.ipynb` — The main Jupyter Notebook containing all Python code, visualizations, and markdown commentary.
* `heart.csv` — The raw clinical dataset (Source: UCI Machine Learning Repository).

## How to Run Locally
1. Clone the repository: `git clone https://github.com/YourUsername/heart-disease-eda.git`
2. Ensure you have Jupyter installed: `pip install jupyter pandas numpy matplotlib seaborn`
3. Launch the notebook: `jupyter notebook`

