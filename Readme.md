# Uber Data Analysis using Python 

## Overview
This project performs **exploratory data analysis (EDA)** on Uber trip data using Python.  
The objective is to analyze ride patterns based on **time, date, trip purpose, and category** and extract meaningful insights from the data.

---

## Dataset
- **File Name:** `UberDataset.csv`
- **Description:** The dataset contains Uber trip records including start date, end date, category, purpose, and locations.

> ⚠️ Ensure that `UberDataset.csv` is located in the same directory as the notebook before running the code.

---

## Technologies Used
- **Python**
- **Pandas** – data manipulation and analysis  
- **NumPy** – numerical computations  
- **Matplotlib** – data visualization  
- **Seaborn** – statistical data visualization  

---

## Notebook Workflow

### 1. Importing Libraries
Required Python libraries are imported for data processing and visualization.

### 2. Loading the Dataset
The dataset is loaded using Pandas and inspected to understand its structure and contents.

### 3. Data Cleaning & Preprocessing
- Handling missing (null) values  
- Converting `START_DATE` and `END_DATE` columns to `datetime` format  
- Cleaning and standardizing categorical columns  

### 4. Feature Engineering
- Extracting **date** and **time** from `START_DATE`
- Categorizing trips into time-of-day buckets:
  - Morning  
  - Afternoon  
  - Evening  
  - Night  

### 5. Exploratory Data Analysis (EDA)
- Trip frequency analysis by:
  - Time of day  
  - Trip purpose  
  - Trip category  
- Visualization using bar plots and count plots

### 6. Insights
- Identifies peak travel times
- Highlights common trip purposes
- Shows usage trends across different times of the day

---

## How to Run the Project
1. Clone or download the repository
2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Uber_Data_Analysis_using_Python.ipynb
4. Run all cells sequentially
### Thanks For Visiting - Vedururu Srinivasa Rao