## Overview

This project performs an Exploratory Data Analysis (EDA) on the Titanic dataset using Python. The analysis investigates survival patterns among passengers based on factors such as gender, passenger class, age, fare, and family size.

The project generates statistical summaries, data cleaning reports, and visualizations to help understand the factors associated with passenger survival.

---

## Features

- Dataset inspection and overview
- Missing value analysis
- Data cleaning and preprocessing
- Overall survival analysis
- Survival analysis by gender
- Survival analysis by passenger class
- Age distribution analysis
- Combined analysis of gender and passenger class
- Fare-based survival analysis
- Family size survival analysis
- Correlation heatmap of numerical features
- Data visualizations using Seaborn and Matplotlib

---

## Technologies Used

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Dataset

The project uses the Titanic dataset containing information about passengers onboard the RMS Titanic.

Key columns include:

| Column | Description |
|----------|-------------|
| Survived | Survival status (0 = No, 1 = Yes) |
| Pclass | Passenger class |
| Sex | Gender |
| Age | Age of passenger |
| SibSp | Number of siblings/spouses aboard |
| Parch | Number of parents/children aboard |
| Fare | Ticket fare |
| Embarked | Port of embarkation |

---

## Installation

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

---

## Dataset Location

Place the dataset in the specified directory and update the path:

```python
DATA_URL = r"C:\Users\Milan\Downloads\titanic.csv"
```

Or place the CSV file in the same folder as the script and use:

```python
DATA_URL = "titanic.csv"
```

---

## Running the Project

Execute the script using:

```bash
python titanic_survival_analysis.py
```

Or:

```bash
python3 titanic_survival_analysis.py
```

---

## Analysis Performed

### 1. Dataset Overview

Displays:

- Number of rows and columns
- Column names
- Data types
- Summary statistics
- Missing values

### 2. Data Cleaning

- Removes duplicate records
- Fills missing Age values using median
- Fills missing Fare values using median
- Fills missing Embarked values using mode

### 3. Overall Survival Analysis

Shows:

- Total survivors
- Total non-survivors
- Survival percentage

### 4. Survival by Gender

Compares survival rates for:

- Male passengers
- Female passengers

### 5. Survival by Passenger Class

Compares survival rates among:

- First Class
- Second Class
- Third Class

### 6. Survival by Age

Analyzes age distribution based on survival outcome.

### 7. Survival by Gender and Class

Examines how gender and passenger class together affected survival.

### 8. Fare Analysis

Compares fare distributions between:

- Survivors
- Non-survivors

### 9. Family Size Analysis

Investigates how family size influenced survival probability.

### 10. Correlation Heatmap

Displays correlations between all numerical variables.

---

## Expected Results

Typical findings include:

- Female passengers had a significantly higher survival rate.
- First-class passengers were more likely to survive.
- Higher ticket fares generally corresponded to higher survival rates.
- Third-class passengers had the lowest survival rate.
- Children tended to have better survival chances than adults.

---

## Visualization Examples

The script generates:

- Count plots
- Bar charts
- Histograms
- Box plots
- Correlation heatmap

All graphs are displayed using Matplotlib and Seaborn.

---

## Project Structure

```text
Titanic-Survival-Analysis/
│
├── titanic_survival_analysis.py
├── titanic.csv
├── README.md
└── requirements.txt
```

---

## Author

Dhruv Rao

---

## License

This project is intended for educational and learning purposes.