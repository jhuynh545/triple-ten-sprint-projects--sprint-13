# triple-ten-sprint-projects--sprint-13

Sweet Lift Taxi aims to predict hourly taxi order volumes at airports to better allocate drivers during peak hours. Using historical data, the goal is to build a predictive model that meets a target RMSE of no more than 48 on the test set.

Key Objectives:

Develop a reliable forecasting model for hourly taxi orders.
Ensure the RMSE metric on the test set does not exceed the threshold of 48.
Provide actionable insights and recommendations based on model performance.

Methodology:

Data Preparation:
Download and preprocess the dataset.
Resample the data at an hourly frequency to align with the prediction objective.

Data Analysis:
Explore patterns in taxi order volumes, such as trends, seasonality, and anomalies.
Identify key features and correlations to inform model development.

Model Training:
Train various machine learning models with different hyperparameters, such as linear regression, decision trees, random forests, and gradient boosting techniques.
Split the dataset, reserving 10% of the initial data as the test sample.

Model Evaluation:
Evaluate models using the RMSE metric to ensure performance standards are met.
Conduct a final test on the reserved test sample.

Deliverables:
A trained model capable of predicting hourly taxi orders with an RMSE ≤ 48 on the test set.
Insights into the models’ performance, including strengths and areas for improvement.
Recommendations for future implementation and scaling.
