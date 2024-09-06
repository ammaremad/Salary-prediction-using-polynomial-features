# Salary Prediction Using Polynomial Regression
## Project Overview
This project focuses on predicting salaries based on job levels using polynomial regression.
The dataset contains information about various job positions, their corresponding levels, and salaries.
The goal is to analyze the relationship between job levels and salaries, visualize the data, handle outliers, and build a predictive model to estimate salaries for different job levels.

## Dataset
The dataset consists of 10 entries with the following columns:
**Position:** The job title.
**Level:** The job level (integer).
**Salary:** The corresponding salary for each position.
Key Steps in the Project

**1.Data Understanding:**
- Load the dataset and explore its structure, including the number of rows and columns.
- Identify the target label (Salary) and the features (Level).
  
**2.Data Preprocessing:**
- Check for missing values and duplicates.
- Obtain statistical measures to understand the distribution of the data.
- Visualize the correlation between features and the target label.
  
**3.Data Visualization:**
- Create scatter plots to visualize the relationship between job levels and salaries.
- Use box plots to identify and handle outliers in the salary data.
  
**4.Feature Engineering:**
- Drop the Position column since the Level column sufficiently represents the job position.
- Normalize the features using MinMaxScaler.

**5.Data Splitting:**
- Split the dataset into training and testing sets to evaluate the model's performance.

**6.Model Building:**
- Apply polynomial regression to capture the non-linear relationship between job levels and salaries.
- Train the model using the training dataset and make predictions on the test dataset.
  
**7.Model Evaluation:**
- Evaluate the model's accuracy using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared value.
  
**Results**
The polynomial regression model achieved an impressive accuracy of 99%, indicating a strong fit to the data. The analysis revealed significant insights into salary distributions across different job levels, including the identification of outliers.

Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn
**Conclusion**
This project demonstrates the effectiveness of polynomial regression in predicting salaries based on job levels. The insights gained from the data analysis can be valuable for organizations in making informed decisions regarding salary structures.

Feel free to explore the code and visualizations in this repository to gain a deeper understanding of the project!
