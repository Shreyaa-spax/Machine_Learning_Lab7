# Machine Learning Lab 7 – Exploratory Data Analysis on Glass Dataset

## Overview

This project demonstrates Exploratory Data Analysis (EDA) on the Glass Identification Dataset using Python. It focuses on understanding the dataset, analyzing the distribution of glass types, and visualizing the numerical features.

The project uses Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn.

## Objectives

- Load and explore the Glass Identification Dataset.
- Understand the dataset structure and statistical properties.
- Check for duplicate records and missing values.
- Analyze the distribution of different glass types.
- Visualize numerical features using different plotting techniques.
- Prepare the data for a classification task.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab / Jupyter Notebook

## Dataset Description

The dataset contains **214 records and 10 columns**.

| Feature | Description |
|---|---|
| RI | Refractive Index |
| Na | Sodium |
| Mg | Magnesium |
| Al | Aluminum |
| Si | Silicon |
| K | Potassium |
| Ca | Calcium |
| Ba | Barium |
| Fe | Iron |
| Type | Glass category |

The `Type` column represents the glass classification, while the remaining columns contain numerical measurements.

## Implementation

### 1. Importing Libraries

The required Python libraries are imported for data manipulation, visualization, and machine learning.

### 2. Loading the Dataset

The Glass Identification Dataset is loaded into a Pandas DataFrame.

### 3. Data Exploration

The following functions are used to inspect the dataset:

- `head()`
- `tail()`
- `info()`
- `describe()`

### 4. Data Quality Checks

The notebook performs the following checks:

- Duplicate records
- Missing values
- Unique values in the `RI` column
- Removal of duplicate records

### 5. Data Visualization

The notebook includes:

- **Bar Plot** – Shows the distribution of glass types.
- **Pie Chart** – Shows the percentage distribution of glass classes.
- **Histograms** – Show distributions of numerical features.
- **Box Plots** – Compare numerical features across glass types.
- **Histograms with KDE** – Show feature distributions and density curves by glass type.

## Libraries Installation

Install the required libraries using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## How to Run

1. Clone this repository:

```bash
git clone <your-repository-url>
```

2. Open the `.ipynb` notebook in Google Colab or Jupyter Notebook.

3. Make sure the Glass dataset CSV file is available.

4. Run the notebook cells sequentially.

## Key Learnings

- Understanding a real-world dataset using Pandas.
- Performing basic data quality checks.
- Using descriptive statistics to summarize numerical data.
- Creating visualizations using Matplotlib and Seaborn.
- Understanding numerical feature distributions.
- Analyzing class distributions.
- Preparing data for a machine learning classification task.

## Conclusion

This lab provides practical experience in Exploratory Data Analysis and Data Visualization using the Glass Identification Dataset. The statistical summaries and visualizations help in understanding the characteristics and distribution of different glass types.

## Author

**Shreya Sharma**

**Machine Learning Lab 6**
