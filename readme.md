# AMCAT EDA (Exploratory Data Analysis)

This project is an Exploratory Data Analysis (EDA) of the AMCAT dataset, which contains information about candidates' academic performance, employment history, and more. 
The goal is to preprocess, clean, and analyze the data to extract meaningful insights and patterns.

## Project Structure

- **Data Cleaning:** Renaming columns, handling missing values, and correcting data inconsistencies.
- **Feature Engineering:** Calculating employment duration and processing date-related columns.
- **Exploratory Data Analysis (EDA):** Insights into the dataset through visualizations and statistical analysis.

## Dataset Description

The dataset was released by Aspiring Minds from the Aspiring Mind Employment Outcome 2015 (AMEO). The study is primarily limited  only to students with engineering disciplines. The dataset contains the employment outcomes of engineering graduates as dependent variables (Salary, Job Titles, and Job Locations) along with the standardized scores from three different areas – cognitive skills, technical skills and personality skills. The dataset also contains demographic features. The dataset  contains  around  40 independent variables and 4000 data points. The independent variables are both continuous and categorical in nature. The dataset contains a unique identifier for each candidate.

### Key Steps in Analysis

1. **Loading Data:**
   - The dataset is loaded using pandas, and initial inspection is done using `info()`, `head()`, and `shape()`.

2. **Data Cleaning:**
   - Column names were made more descriptive for better readability.
   - Missing values were identified and handled accordingly.
   
3. **Feature Engineering:**
   - Employment duration was calculated for each candidate based on joining and leaving dates.

4. **Exploratory Analysis:**
   - Insights about candidate distribution, grade analysis, and tenure were explored.
   - Further visualizations were added for deeper insights into patterns.

### Findings

- The dataset contains a mix of academic and employment history, which provides insight into candidate backgrounds and career trajectories.
- Certain patterns were observed in grades and employment duration, which can guide decision-making for hiring or further analysis.

## Improvements & Next Steps

- **Data Visualization:** More graphs and charts to better understand distributions and trends.
- **Missing Value Handling:** Imputation or other strategies could be further refined.
- **Advanced Analysis:** Future iterations could include clustering or regression analysis to predict candidate success or trends in employment history.

## Getting Started

To run this project:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/amcat-eda.git

