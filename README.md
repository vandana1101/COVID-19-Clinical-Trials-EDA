# COVID-19-Clinical-Trials-EDA

**Objective:**  
The aim of this project is to explore and analyze a dataset of COVID-19 clinical trials from ClinicalTrials.gov using Python, focusing on understanding key characteristics like trial status, phases, study designs, demographics, and trends over time. The goal is to gain valuable insights that could assist in decision-making and further research in the domain of clinical trials for COVID-19.

**Tools Used:**  
- Python (with Pandas, Matplotlib, and Seaborn)
- Excel (for data cleaning and initial exploration)
- 
**Methodology:**  
1. **Data Loading & Initial Exploration:**  
   - Imported the dataset using Pandas and performed an initial examination of the data, including viewing column names, data types, and checking for missing values.
   
2. **Data Cleaning:**  
   - Removed columns with excessive missing data (e.g., 'Study Documents' and 'Results First Posted').
   - Dropped duplicate rows to ensure the dataset's uniqueness.
   - Handled missing values by filling or removing rows with a significant amount of missing data.

3. **Univariate and Bivariate Analysis:**  
   - Performed frequency analysis on categorical variables like 'Status', 'Phases', and 'Age Group' to understand the distribution.
   - Explored relationships between key variables using crosstabs and visualizations, like 'Status vs. Phases' to analyze how clinical trial phases are distributed across various trial statuses.

4. **Time Series Analysis:**  
   - Examined the temporal trends of COVID-19 clinical trials by analyzing the start dates and plotting the number of trials over time.

5. **Data Visualization:**  
   - Generated visualizations such as bar charts for categorical data and line charts for time-series data to highlight important insights.

6. **Conclusion:**  
   - The analysis revealed trends such as the dominance of completed trials, an increasing number of trials over time, and the predominance of adult populations in trials.

7. **Results & Insights:**  
   - Key findings included the increasing number of trials over the pandemic period, trial status distributions, and insights into the most common phases and conditions studied.
   
**Outcome:**  
This project provides a comprehensive EDA of COVID-19 clinical trials, uncovering patterns and trends that offer valuable insights into the state of clinical research during the pandemic. It serves as a foundation for further analysis and potential predictive modeling.
