# Ad-Campaign-Performance-Prediction

🔍 Overview

During my time running a social media marketing agency, one of the biggest challenges we faced was predicting the success rate of an ad campaign before launching it. Without data-driven insights, it was difficult to determine the potential effectiveness of different campaigns.

To address this issue, I developed a machine learning-based prediction model that estimates the likelihood of a campaign's success based on key metrics such as budget, duration, clicks, conversion rates, and CPC. Although this model is currently trained on a synthetic dataset, it can be easily adapted to work with real-world data for more accurate and actionable insights. 🚀


📊 Exploratory Data Analysis (EDA)
The dataset undergoes comprehensive EDA with visualizations to understand the relationships between features:

Histogram: Budget distribution
Boxplot: Clicks vs. success
Scatterplot: CTR vs. conversion rate
Heatmap: Feature correlation analysis
🤖 Machine Learning Models Used
The project compares multiple models to determine the best one for prediction:

Logistic Regression
Random Forest
Gradient Boosting
XGBoost (Extreme Gradient Boosting)
The best model is selected based on accuracy, precision, recall, and F1-score.

📈 Results
Best Model: ✅ Random Forest
Accuracy Achieved: 0.9972144846796658
Predicted Success Rate: 89.70%

🛠️ Tech Stack
Python
Pandas, NumPy (Data Manipulation)
Matplotlib, Seaborn (Data Visualization)
Scikit-learn, XGBoost (Machine Learning)
SMOTE (Handling Imbalanced Data)
