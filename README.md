# HR Employee Attrition Analysis

This project aims to analyze the employee attrition data to understand patterns and factors contributing to employee turnover. The analysis includes examining data distributions, detecting outliers, visualizing categorical data distributions, creating pie charts, and plotting correlation matrices and other visualizations.

## Project Overview

The main objectives of this project are:

- To explore and clean the dataset.
- To visualize the distributions of various features.
- To detect and plot outliers in numerical columns.
- To analyze categorical columns and their relationship with employee attrition.
- To compute and visualize the correlation matrix for numerical features.
- To provide insights into employee attrition patterns.

## Dataset

The dataset used for this analysis is the `HR-Employee-Attrition.csv`. It contains information about employees, including their demographics, job roles, satisfaction levels, and whether they have left the company (attrition).

## Steps and Analysis

### 1. Data Loading and Initial Exploration

- Load the dataset using pandas.
- Display the first few rows, shape, columns, summary statistics, and data types.
- Check for null and duplicated values.

### 2. Categorical Data Analysis

- Identify object type columns and print unique values and their counts.
- Plot the distribution of each categorical column grouped by the Attrition column using count plots.
- Generate advanced pie charts for categorical columns to visualize their distribution.

### 3. Outlier Detection

- Detect and plot outliers for numerical columns using box plots and the IQR method.

### 4. Department and Business Travel Analysis

- Analyze the number of employees in each department and their business travel frequency.
- Visualize the results using bar plots with custom color palettes.

### 5. Correlation Analysis

- Calculate and visualize the correlation matrix for numerical features using a heatmap.

### 6. Attrition Analysis by Education Field and Job Role

- Split the dataframe based on the Attrition column.
- Calculate the distribution of EducationField and JobRole for employees who have left and who have stayed.
- Visualize the results using pie charts.

### 7. Career Growth Analysis

- Plot a line plot to visualize the relationship between YearsInCurrentRole and JobLevel.

## Results

The analysis provides various insights into employee attrition, including:

- Patterns in categorical data distribution by attrition status.
- Outliers in numerical columns.
- Correlations between numerical features.
- Distribution of employees across departments and business travel frequency.
- Education field and job role distribution by attrition.
- Career growth patterns based on years in the current role.

## Conclusion

This analysis helps in understanding the factors contributing to employee attrition and provides a basis for further investigation into improving employee retention strategies.

## Visualizations

Various plots and charts are generated throughout the analysis to visualize the data and provide insights. These include:

- Count plots
- Box plots
- Pie charts
- Bar plots
- Heatmap
- Line plot

## Repository Structure

- `HR-Employee-Attrition.csv`: The dataset file.
- `HRAnalytics.ipynb`: The Jupyter Notebook containing the data analysis and visualization code.
- `README.md`: This readme file.

## Usage

Run the Jupyter Notebook `HRAnalytics.ipynb` to perform the analysis and generate visualizations. To run the notebook, follow these steps:

1. Install the necessary libraries (if not already installed):

    ```bash
    pip install pandas numpy matplotlib seaborn plotly
    ```

2. Open the Jupyter Notebook:

    ```bash
    jupyter notebook HRAnalytics.ipynb
    ```

3. Execute the cells sequentially to reproduce the analysis and visualizations.
 
## Repository Link

You can find the repository (https://github.com/onniep/HR-Employee-Attrition.git).