# EDA-on-Salaries-of-Different-Data-Science-Fields
Data Analysis Exploratory Project Report: Salaries of Different Data Science Fields
Introduction
This data analysis exploratory project aims to investigate the salaries of different data science fields in the data science domain. The dataset used for this analysis contains information on various factors related to salaries, including work year, experience level, employment type, job title, salary, currency, remote work ratio, company location, and company size.

Methodology
Dataset Loading and Cleaning
The dataset was loaded into a pandas DataFrame.
Initial data cleaning steps were performed, such as handling missing values and correcting data types.
Exploratory Data Analysis (EDA)
The dataset was analyzed to gain insights into the distribution of salaries, experience level, job titles, employment types, remote work ratios, and company sizes.
Summary statistics were calculated to understand the central tendencies and spread of the salary data.
Data visualizations, including histograms, box plots, bar plots, and scatter plots, were created to visualize the relationships between variables and identify potential patterns.
Correlation Analysis
Correlation analysis was conducted to examine the relationships between variables, particularly focusing on the relationship between salary and other factors such as experience level, job title, and employment type.
Heatmaps or correlation matrices were generated to visualize the strength and direction of correlations between variables.
Data Visualization
Various data visualization techniques were employed to present the findings effectively.
Visualizations included bar plots, box plots, scatter plots, and line plots to showcase trends, patterns, and comparisons related to salaries across different variables.
Predictive Modeling
Linear regression and Random Forest regression models were developed and trained to estimate salaries based on the given features.
The models were evaluated using the Mean Squared Error (MSE) metric to quantify prediction errors.
Recommendations for Further Analysis and Improvement
Exploring additional relevant features that may have an impact on salaries.
Experimenting with different regression algorithms and ensemble methods to improve prediction accuracy.
Continuously evaluating and iterating on the models to achieve better predictions.
Findings and Observations
The analysis of the dataset yielded the following findings and observations:

The dataset contains information about salaries in the data science domain, including features such as work year, experience level, employment type, job title, remote ratio, and company-related details.
Exploratory Data Analysis revealed the distribution of salaries and provided insights into the distributions and relationships of various variables.
Data cleaning and preprocessing steps were performed to handle missing values and ensure data consistency.
Data visualization helped identify trends and patterns in salary distributions across different variables.
Correlation analysis showed the relationships between variables and their impact on salary levels.
The linear regression model produced a Mean Squared Error (MSE) of 167387525025.40994, indicating relatively lower prediction errors compared to the Random Forest regression model, which had an MSE of 316318636725.93024.
Further analysis and improvement of the models are necessary to enhance their accuracy in predicting salaries based on the given features.
Recommendations include exploring additional relevant features, experimenting with different regression algorithms and ensemble methods, and continuously evaluating and iterating on the models to achieve better predictions.
Conclusion and Insights
Based on the analysis, several conclusions and insights were drawn:

Experience level is positively correlated with salary, indicating that as experience increases, salaries tend to rise as well.
Job titles such as "Data Scientist" and "Data Engineer" tend to have higher salaries compared to other job titles.
Full-time employees generally earn higher salaries compared to part-time or contract workers.
The amount of remote work has a slight positive correlation with salary, suggesting that individuals with more remote work opportunities may earn slightly higher salaries.
Company size does not show a clear correlation with salary.
In conclusion, this project provides insights into the salaries of different data science fields in the Data Science Domain. The analysis highlights the relationships between various factors and salary levels and presents predictive models for estimating salaries based on relevant features. However, the models' accuracy can be further improved through feature engineering, model selection, hyperparameter tuning, and the inclusion of more comprehensive and diverse data.

This project serves as a starting point for understanding and predicting salaries in the data science domain, and it provides a foundation for future research and analysis in this field.
