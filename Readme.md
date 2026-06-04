# Government Data Analyst – Air Quality Analysis

## Overview

This project analyzes Indian Air Quality data obtained from Government Open Data sources. The objective is to explore pollution trends, identify the most and least polluted cities, and build a Natural Language Query System that allows users to ask questions about the dataset.

The project combines data cleaning, exploratory data analysis, visualization, and an interactive Gradio web application.

---

## Dataset Information

Source: Government Open Data Platform (India)

Dataset Features:

* Country
* State
* City
* Station
* Last Update
* Latitude
* Longitude
* Pollutant ID
* Pollutant Minimum Value
* Pollutant Maximum Value
* Pollutant Average Value

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Gradio

---

## Project Workflow

### 1. Data Collection

* Loaded Air Quality dataset from Government Open Data.

### 2. Data Cleaning

* Converted date columns.
* Removed missing pollution records.
* Checked dataset consistency.

### 3. Exploratory Data Analysis

* Pollutant distribution analysis.
* City-wise pollution analysis.
* Top polluted cities identification.

### 4. Natural Language Query Engine

Implemented support for questions such as:

* Which city has highest pollution?
* Which city has lowest pollution?
* Show top 10 polluted cities.

Unsupported questions are handled gracefully.

### 5. Interactive Dashboard

Built a Gradio-based interface for querying the dataset interactively.

---

## Key Findings

* Byrnihat was identified as the most polluted city.
* Cuddalore was identified as the least polluted city.
* CO and OZONE were among the most frequently recorded pollutants.
* Significant variation in pollution levels exists across Indian cities.

---

## Example Questions

### Highest Pollution City

Input:

```text
Which city has highest pollution?
```

Output:

```text
The most polluted city is Byrnihat with an average pollution level of 99.60
```

---

### Lowest Pollution City

Input:

```text
Which city has lowest pollution?
```

Output:

```text
The least polluted city is Cuddalore with an average pollution level of 2.00
```

---

### Unsupported Question

Input:

```text
What is the crime rate in Delhi?
```

Output:

```text
Sorry, I cannot answer this question using the available dataset.
```

---

# Visualizations

## Pollutant Distribution

![Pollutant Distribution](images/Number of records pollutant.png)

---

## Top 10 Most Polluted Cities

![Top Polluted Cities](images/top_10_polluted_cities.png)

---

## Query Engine Results

![Query Engine Results](images/query_engine_results.png)

---

## Gradio Interface

![Gradio Interface](images/gradio_interface.png)

---

## Project Structure

```text
Government-Data-Analyst/
│
├── Government_Data_Analyst.ipynb
├── README.md
├── set.csv
│
└── images/
    ├── pollutant_distribution.png
    ├── top_10_polluted_cities.png
    ├── query_engine_results.png
    └── gradio_interface.png
```

---

## Conclusion

This project demonstrates practical skills in:

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Data Visualization
* Natural Language Query Processing
* Interactive Dashboard Development

The solution provides an easy-to-use interface for exploring Government Air Quality datasets through simple natural-language questions.
