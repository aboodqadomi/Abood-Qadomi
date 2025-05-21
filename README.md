# Abood-Qadomi
Project Overview and Objectives

This project explores player behavior in a competitive action game using Python-based analytics. By analyzing in-game telemetry data, we aimed to identify gameplay patterns, cluster player sessions, and build machine learning models to predict game outcomes. The ultimate goal is to inform better game design through data-driven insights.

Technologies Used

Category

Tools/Libraries

Game Engine (optional)

Unity or Unreal Engine (if applicable)

Programming Language

Python

Data Analysis

pandas, numpy

Visualization

seaborn, matplotlib

Statistics

scipy.stats

Machine Learning

scikit-learn (KMeans, LinearRegression)

Data Collection Methodology

The dataset used takes data Fortnite telemetry logs:

Each row = one game session

Columns include eliminations, hits, materials used, damage taken, accuracy, distance traveled, etc.

Data is assumed to be collected from in-game telemetry tools and exported as CSV.

Machine Learning Implementation

We used two ML models:

KMeans Clustering

Inputs: Eliminations, Hits, Distance Traveled

Output: Cluster labels grouping players into behavioral categories

Linear Regression

Inputs: Hits, Materials Used, Distance Traveled

Output: Predicted Damage Taken

These models were trained using scikit-learn.

Future Additions (Optional)

Real-time dashboard using Streamlit

Classification models (e.g., player churn prediction)

Additional in-game metrics (weapon usage, team strategy)
