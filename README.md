# Salary Data Analysis Project

## Project Overview
This project analyzes salary data to gain insights into various aspects of compensation across different industries, job titles, and locations. The analysis is performed using Python with pandas for data manipulation and analysis.

## Data Description
The dataset (`salaries.csv`) contains salary information with the following characteristics:
- File size: 4.7MB
- Contains comprehensive salary data across multiple dimensions
- Includes information about job titles, locations, and compensation details

## Project Structure
- `salaries.csv`: The main dataset containing salary information
- `read_salaries.ipynb`: Jupyter notebook containing the data analysis code
- `README.md`: This documentation file

## Analysis Steps
The analysis in the Jupyter notebook performs the following operations:
1. Data Loading and Initial Exploration
   - Importing necessary libraries (pandas)
   - Loading the CSV file into a pandas DataFrame
   - Displaying the first few rows of the dataset

2. Data Information
   - Displaying dataset structure and information
   - Showing data types and non-null counts for each column

3. Statistical Analysis
   - Computing basic statistics for numerical columns
   - Providing summary statistics of the dataset

## Requirements
- Python 3.x
- Required Python packages:
  - pandas
  - jupyter (for running the notebook)

## Installation
1. Install the required packages:
```bash
pip install pandas jupyter
```

2. Run the Jupyter notebook:
```bash
jupyter notebook read_salaries.ipynb
```

## Usage
1. Open the Jupyter notebook
2. Run the code cell to perform the analysis
3. View the results which include:
   - First few rows of the dataset
   - Dataset information
   - Basic statistical analysis

## Future Enhancements
- Add more detailed analysis of specific salary trends
- Include data visualization using matplotlib or seaborn
- Perform more advanced statistical analysis
- Add machine learning models for salary prediction 