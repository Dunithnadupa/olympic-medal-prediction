🏅 Olympic Medal Prediction Using Linear Regression

📌 Project Overview

• This project predicts the number of Olympic medals won by countries using historical Olympic data. A Linear Regression model was developed to estimate medal counts based on key performance indicators such as number of athletes and previous medal counts.

🎯 Objective

• To build an end-to-end machine learning pipeline capable of predicting Olympic medal counts and evaluating model performance using appropriate regression metrics.

📊 Dataset

The dataset contains:

• Team name
• Country
• Year
• Number of athletes
• Average age
• Previous medal count
• Current medal count (target variable)

⚙️ Methodology

1️⃣ Data Preprocessing

• Removed missing values
• Selected relevant features
• Split data into training (<2012) and testing (≥2012)

2️⃣ Exploratory Data Analysis (EDA)

• Visualized relationships using regression plots
• Analyzed medal distribution using histograms

3️⃣ Model Development

• Model: Linear Regression
• Predictors:
     • Athletes
     • Previous medals
• Target:
     • Medals

4️⃣ Model Evaluation

• Metric: Mean Absolute Error (MAE)
• Error analysis performed per team
• Error ratio calculated to assess prediction reliability

📈 Results

• The model demonstrates a reasonable predictive relationship between athlete participation, previous medal performance, and final medal outcomes. Error distribution analysis highlights variability between teams.

🛠 Technologies Used

• Python
• Pandas
• NumPy
• Scikit-learn
• Seaborn
• Matplotlib

🚀 Future Improvements

• Add GDP, host country, and sport-level features
• Try Ridge / Lasso regression
• Apply ensemble models (Random Forest, XGBoost)
• Deploy as a web application

