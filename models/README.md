🧠 VaxImpact ML Project – Vaccine Outcomes
📌 Project Overview

This project applies Machine Learning (ML) to analyze the relationship between vaccination status and patient health outcomes (hospitalization and death).
Using multiple models, I compare predictions for Unvaccinated, Vaccinated, and Boosted patient groups to demonstrate how vaccination correlates with improved outcomes.

💡 Key Message:

The data shows that unfortunate outcomes such as hospitalization and death are significantly higher in unvaccinated individuals, reinforcing the importance of vaccines.

⚙️ Tech Stack

Python 3.10+

Pandas, NumPy → data cleaning & feature engineering

Matplotlib, Seaborn → visualizations & outcome comparisons

Scikit-learn → ML modeling and evaluation

🧪 Models Implemented

I trained and compared multiple models to predict patient outcomes:

Decision Tree Regressor

Random Forest Regressor

Each model was tested across three vaccination groups:

Unvaccinated (y_pred, y_pred1)

Vaccinated (y_pred2, y_pred3)

Boosted (y_pred4, y_pred5)

📊 Visualizations

The notebook includes the following:

1. Model Performance Comparison

Side-by-side charts comparing predicted vs. actual outcomes across different models.

2. Vaccination Status vs Outcomes

Clean bar charts highlighting how hospitalization and death rates vary across:

Unvaccinated

Vaccinated

Boosted

📌 The visualizations clearly show that unvaccinated groups experience the highest rates of hospitalization and death, while boosted groups experience the lowest.

🚀 How to Run

Clone this repo:

git clone https://github.com/yourusername/patient-intelligence-ml.git
cd patient-intelligence-ml


Install dependencies:

pip install -r requirements.txt


Run the notebook:

jupyter notebook patient_ml_analysis.ipynb

✅ Key Learnings

Practiced data preprocessing, model training, and evaluation.

Learned to visualize ML results with intuitive dashboards.

Applied ML in a real-world public health scenario, delivering insights that matter.

📢 Final Note

This project is both a technical achievement and a public health message:
Vaccines save lives. Data proves it.
