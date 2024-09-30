# 24566011_Machine-learning

Assignment 1 - DAC-501 Machine Learning Course 
Overview 
This assignment focuses on performing an exploratory data analysis (EDA) of a dataset selected from the Kaggle library. The aim is to understand the dataset's structure, identify key patterns, and draw preliminary insights that will inform further analysis or modeling.

Dataset Selection Dataset Name: [Stroke Prediction Dataset] 
Link to Kaggle Dataset: [https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset?resource=download] 

Description: 
Stroke Prediction Dataset Overview Purpose: The stroke prediction dataset is designed to help analyze and predict the likelihood of stroke occurrences based on various health and demographic factors. This dataset can be used to build predictive models and perform exploratory data analysis (EDA) to understand the relationships between different variables and stroke risk.

Common Features in the Dataset are as follows:
1. Age: The age of the individual (often measured in years). This is a continuous variable that significantly impacts stroke risk.
2. Gender: The gender of the individual, typically categorized as "Male" or "Female." Gender can influence the risk of stroke.
3. Hypertension: A binary variable indicating whether the individual has hypertension (high blood pressure). Values are usually represented as 0 (No) and 1 (Yes).
4. Heart Disease: A binary variable indicating whether the individual has a history of heart disease. Like hypertension, it is usually represented as 0 (No) and 1 (Yes).
5. Ever Married: A binary variable indicating whether the individual has ever been married (0 for No, 1 for Yes). Marital status can influence lifestyle factors related to health.
6. Work Type: A categorical variable describing the individual's type of employment, such as "Private," "Self-employed," "Govt_job," "Never_worked," or "Children."
7. Residence Type: A categorical variable indicating whether the individual lives in an "Urban" or "Rural" area.
8. Average Glucose Level: A continuous variable measuring the average glucose level in the blood. Higher glucose levels can be associated with diabetes, which is a risk factor for stroke.
9. Body Mass Index (BMI): A continuous variable representing the individual's body mass index, calculated from their height and weight.
10. BMI is an important indicator of health risk. Smoking status : A categorical variable with 'formerly smoked', 'never smoked', 'smokes' and 'unknown'.
11. Stroke: The target variable indicating whether the individual has experienced a stroke (0 for No, 1 for Yes).

Objectives:
The primary objectives of this assignment are: 
To explore the dataset and understand its structure, including data types, missing values, and distributions. 
To visualize key trends and patterns within the data using appropriate statistical and graphical methods. 
To formulate hypotheses based on observed data characteristics and provide insights that could inform subsequent machine learning tasks.

Possible Analyses : 
1. Descriptive Statistics: 
Summary statistics for continuous variables (e.g., mean, median, standard deviation). 
Frequency distribution of categorical variables (e.g., counts of each work type). 
2. Data Visualization: Histograms for age and average glucose level to understand their distributions. Bar plots for categorical variables like work type and residence type. Box plots to visualize the relationship between stroke and other variables.
3. Correlation Analysis: Compute correlation coefficients to examine relationships between numerical features and stroke occurrence. Use heatmaps to visualize correlation matrices.
4. Statistical tests: Chi-sqauare, t-test and z-test.
5. Hypothesis Testing: Conduct tests to determine if there are statistically significant differences in stroke rates across different age groups, work types, or other factors.

Steps Performed : 
1. Data Loading: The dataset was loaded into a Pandas DataFrame for analysis.
2. Data Cleaning: Missing values were addressed, and data types were converted as necessary.
3. Descriptive Statistics: Summary statistics were generated to understand the central tendencies and dispersion of the data.
4. Data Visualization: Various plots (e.g., histograms, box plots, scatter plots) were created to visualize distributions and relationships among variables.
5. Correlation Analysis: Correlation coefficients were computed to identify relationships between numerical features.
6. Statistical tests: Perform Chi-sqauare, t-test and z-test.
7. Deriving conclusions

Tools and Libraries used : 
Python, Pandas, Matplotlib, Seaborn, scipy, numpy

Insights One Might Derive Age Impact: 
1. Understanding how age correlates with stroke risk can help identify high-risk groups. 
2. Hypertension and Heart Disease: Analyzing the influence of hypertension and heart disease on stroke occurrences can guide preventive measures. 
3. Lifestyle Factors: Examining work type, residence type, smoking status and marital status can provide insights into lifestyle factors that contribute to stroke risk.
4. Health Indicators: Assessing how average glucose levels and BMI relate to stroke risk can highlight the importance of managing these health indicators.

Conclusion :
The stroke prediction dataset serves as a valuable resource for understanding the factors contributing to stroke risk. Through exploratory data analysis and predictive modeling, insights gained from this dataset can inform public health initiatives and individual health management strategies aimed at reducing stroke occurrences.

Future Work Further analyses, including predictive modeling and hypothesis testing, will build upon the findings from this exploratory analysis.

Author [Kachhadia Harsh Nagjibhai - 24566011]
