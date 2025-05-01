# ✈️ Flight Price Prediction Project
This project aims to predict the price of flight tickets using machine learning algorithms. By applying feature engineering, visualization, and regression techniques, the model tries to understand which factors affect ticket pricing the most.

📂 Dataset Information
File Used: Flight_Price_Train.csv

Rows: 10,683

Columns: 11

Target Variable: Price

🔍 Project Workflow
✅ 1. Data Loading & Basic Exploration
Imported essential libraries (numpy, pandas, matplotlib, seaborn)

Loaded the dataset

Explored dataset shape, top 5 rows, info, null values, and data types

Checked for duplicates

🧹 2. Data Cleaning & Feature Engineering
Handled missing values in Route and Total_Stops

Extracted:

Day, Month from Date_of_Journey

Hour, Minute from Dep_Time and Arrival_Time

Cleaned the Duration column (standardized inconsistent formats)

Dropped redundant columns (Date_of_Journey, Dep_Time, etc.)

Applied:

Label Encoding for Total_Stops

One-Hot Encoding for Airline, Source, Destination

📊 3. Data Visualization
Used matplotlib and seaborn for:

Flight price distribution

Boxplots for Airline vs Price

Price variation by number of stops

Correlation heatmap

🤖 4. Model Building & Evaluation
Trained on the processed dataset using the following algorithms:

Model	R² Score (Accuracy)	RMSE	MAE
Linear Regression	~66%	Moderate	Moderate
Decision Tree Regressor	~85%	Lower	Lower
Random Forest Regressor	~91–95%	Lowest	Lowest

Best model: ✅ Random Forest Regressor

Performed Hyperparameter Tuning using GridSearchCV

📈 Goal
To accurately predict flight prices using machine learning, enabling data-driven decisions in pricing strategies and customer insights.

🛠️ Tools & Libraries Used
Python

pandas, numpy

matplotlib, seaborn

scikit-learn

📌 Conclusion
This project demonstrates how effective feature engineering and ensemble models like Random Forest can lead to high-performance price prediction models.

