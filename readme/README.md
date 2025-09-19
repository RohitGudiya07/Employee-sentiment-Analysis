Employee Sentiment Analysis:
This project analyzes employee emails to measure sentiment, rank employees, detect flight risks, and predict trends using machine learning.

Flight Risk Employees:
Note: Replace the list below with your actual employees from output/flight_risk_employees.csv.

bobette.riner@ipgdirect.com
don.baughman@enron.com
eric.bass@enron.com
john.arnold@enron.com
johnny.palmer@enron.com
kayne.coulter@enron.com
lydia.delgado@enron.com
patti.thompson@enron.com
rhonda.denton@enron.com
sally.beck@enron.com

How to Run the Notebook:
1. Open notebooks/Employee_Sentiment_Analysis.ipynb in Jupyter Notebook or VS Code.
2. Make sure the data/test.csv file is present.
3. Run the notebook cell by cell in the following order:
Data preprocessing
Sentiment labeling
EDA & visualizations
Employee scoring & ranking
Flight risk identification
Predictive modeling
4. The outputs will be saved in:
output/ → CSV files (processed messages, scores, rankings, model metrics)
visualizations/ → Charts and plots

Outputs & Visualizations
CSV Files in output/ folder:

processed_messages.csv (Cleaned and preprocessed messages)
employee_monthly_scores.csv (Monthly sentiment scores per employee)
employee_rankings.csv (Top positive & negative employees per month)
flight_risk_employees.csv (Employees flagged as flight risk)
model_metrics.csv (Linear Regression evaluation metrics)
feature_importance.csv (Feature coefficients)

Charts in visualizations/ folder:
sentiment_distribution.png
monthly_message_counts.png
message_length_boxplot.png
top_employees_per_month.png
flight_risk_events.png
actual_vs_predicted.png
feature_importance.png
residuals.png

Key Insights & Recommendations:
Employees with repeated negative messages may indicate disengagement or potential flight risk.
Top positive employees can be recognized or rewarded.
Predictive modeling helps anticipate sentiment trends and plan HR interventions.

Project by: Rohit Gudiya
Date: September 2025
