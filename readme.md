# AMCAT EDA (Exploratory Data Analysis)

This project is an in-depth exploratory analysis of the AMCAT dataset, focusing on candidates' academic performance, employment history, and other demographic details. The primary goal is to preprocess, clean, and extract insights to understand the dataset's structure and trends.

## Project Structure

1. **Data Cleaning**: Renaming columns for clarity, handling missing values, and addressing inconsistencies.
2. **Feature Engineering**: Adding new features like employment duration and age.
3. **Exploratory Data Analysis (EDA)**: Statistical and visual analysis to uncover patterns and insights.

## Dataset Description

The dataset, released by Aspiring Minds in 2015, provides employment outcomes for engineering graduates, including salaries, job titles, and locations. It also contains standardized scores in cognitive, technical, and personality areas, along with demographic details. The dataset includes:

- 40 variables (continuous and categorical)
- 4000 data points
- Candidate employment history, academic performance, and demographic details

## Key Steps in the Analysis

### 1. **Loading Data**
- The dataset was loaded using `pandas`.
- Initial inspection was done via `info()`, `head()`, and `shape()` to understand data structure.

### 2. **Data Cleaning**
- Column names were updated for clarity (e.g., 'DOJ' to 'DateOfJoining').
- Missing values were identified and handled.
  
### 3. **Feature Engineering**
- **Employment Duration**: Calculated based on joining and leaving dates.
- **Age**: Calculated using the date of birth.

### 4. **Exploratory Data Analysis (EDA)**

#### Univariate Analysis:
- **Target Variable (Salary)**: The average salary is slightly higher than the median, suggesting skewness.
- The dataset shows salary inequality with outliers, confirmed by skewness (6.45) and kurtosis (80.93).

#### Bivariate Analysis:
- **Salary vs. Categorical Variables**: Key findings include differences in salary across job designations, cities, and education.
- **Salary vs. Numerical Variables**: Positive correlation with employment duration and work experience; weak correlations with academic grades.

### 5. **Visualizations**
- **Histogram & PDF of Salary**: Shows a right-skewed distribution with salary clusters between 1.5 and 5 lakhs.
- **Box Plot of Salary**: Highlights outliers earning significantly more than the median salary.
- **Regression Plots**: Relationships between salary and numerical variables such as work experience and CGPA.

## Key Findings

- **Salary Distribution**: A majority of candidates earn between 1.5 and 5 lakhs, with a few outliers skewing the distribution.
- **Job Designation**: Higher salaries for roles like machine learning engineers; wider salary spreads in technical roles.
- **Employment Status**: Currently employed candidates have more compressed salary ranges.
- **Academic Performance**: Weak correlation between 10th/12th grade marks and salary; employment duration shows the strongest correlation with salary.

## Statistical Insights

- **Chi-Square Test**: Gender and specialization are dependent, indicating a significant association between these variables.
- **Correlation Analysis**: Employment duration has the strongest positive correlation with salary, while college-related factors show weaker relationships.

## Conclusion

This analysis provides a comprehensive view of the AMCAT dataset, revealing insights into employment trends, salary distribution, and academic impacts on career trajectories.

## Next Steps

- **Further Data Visualization**: Explore more detailed graphs for deeper insights.
- **Predictive Modeling**: Use regression or clustering models to predict candidate success or salary outcomes.

## Getting Started

To run this project:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/amcat-eda.git
