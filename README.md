\# Calories Burned Prediction using Machine Learning



\## Project Overview



This project aims to predict calories burned during exercise sessions using machine learning models.



The dataset contains information about gym members, including physical characteristics, workout details, heart rate, and lifestyle factors.



\## Dataset



Dataset:

Gym Members Exercise Tracking Dataset (Kaggle)



The dataset includes features such as:



\- Age

\- Gender

\- Weight

\- Height

\- Average BPM

\- Session Duration

\- Fat Percentage

\- Water Intake

\- Workout Frequency

\- Experience Level



Target variable:



\- Calories Burned



\## Data Analysis (EDA)



Performed exploratory data analysis including:



\- Dataset information and statistical summary

\- Missing value checking

\- Correlation analysis

\- Heatmap visualization

\- Calories distribution analysis using histogram



\## Feature Engineering



Applied:



\- Label Encoding for Gender

\- One-Hot Encoding for Workout Type



Selected important features based on correlation analysis:



\- Session Duration

\- Experience Level

\- Fat Percentage

\- Workout Frequency

\- Water Intake

\- Average BPM



\## Machine Learning Models



Implemented and compared:



\### Linear Regression



Evaluation:



\- R² Score

\- MAE

\- RMSE



\### Random Forest Regressor



Evaluation:



\- R² Score

\- MAE

\- RMSE



\## Results



Linear Regression:



\- R²: 0.945

\- MAE: 53.4

\- RMSE: 67.6



Random Forest:



\- R²: 0.949

\- MAE: 52

\- RMSE: 64



\## Technologies Used



\- Python

\- Pandas

\- NumPy

\- Matplotlib

\- Seaborn

\- Scikit-learn

\- Jupyter Notebook



\## Future Improvements



\- Hyperparameter tuning

\- Cross-validation

\- Feature importance analysis

\- Model deployment

