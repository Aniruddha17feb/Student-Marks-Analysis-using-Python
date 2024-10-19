# Student Marks Analysis Project

## Overview
This project focuses on analyzing student score data in three subjects: math, reading, and writing. The dataset contains information about various factors such as gender, parental education, marital status, and transport means. The goal is to extract meaningful insights about the relationships between these factors and student performance.

## Libraries Used
- **Numpy**: For numerical operations
- **Pandas**: For data manipulation and analysis
- **Matplotlib**: For data visualization
- **Seaborn**: For advanced statistical visualizations

## Data Overview
The dataset includes the following columns:
- **Gender**: Male/Female
- **ParentEduc**: Parental education level
- **ParentMaritalStatus**: Marital status of parents
- **MathScore**: Student's math score
- **ReadingScore**: Student's reading score
- **WritingScore**: Student's writing score
- **TransportMeans**: Mode of transport used by students
- **EthnicGroup**: Ethnic group the student belongs to

## Key Features
- **Data Cleaning**: Handled missing values and dropped unnecessary columns.
- **Exploratory Data Analysis (EDA)**: Generated various charts and visualizations to explore relationships in the data.
  - **Gender distribution**: Visualized the male/female ratio.
  - **Parental education and student performance**: Analyzed how parental education affects student scores.
  - **Parental marital status**: Investigated the negligible impact of marital status on scores.
  - **Outlier detection**: Identified outliers in the scores using interquartile range (IQR).
  - **Distribution of scores**: Created histograms and boxplots to show the spread of scores.
  - **Ethnic group distribution**: Visualized the proportion of students from different ethnic groups.
  
## Insights
- Students with parents holding higher educational degrees, especially Master's degrees, performed better on average.
- The marital status of parents had little to no effect on student scores.
- Outliers were identified in math, reading, and writing scores, which could indicate students needing extra support.

## Visualizations
- Count plots for gender distribution
- Heatmaps showing the impact of parental education and marital status
- Boxplots for score distributions and outlier detection
- Histograms for understanding score distributions
- Pie charts for ethnic group proportions

## Conclusion
This analysis provided valuable insights into the factors influencing student performance. The findings can help educators understand how various socio-economic factors relate to student success and guide them in improving academic outcomes.

## How to Run the Code
1. Clone the repository.
2. Install the required libraries:
   ```bash
   pip install numpy pandas matplotlib seaborn
