# Crime Analysis in Los Angeles (2020–2024)

## Overview

This project is an Exploratory Data Analysis (EDA) of crime incidents reported in Los Angeles between 2020 and 2024. The analysis was completed using Python and Pandas to explore crime patterns, identify trends, and answer questions related to crime types, locations, and reporting times.

The goal of this project is to better understand crime patterns and provide data-driven insights that can support public safety planning and decision-making.

---

## Problem Statement

Between 2020 and 2024, more than one million crime incidents were reported across 21 areas in Los Angeles. With such a large amount of data, it is difficult to identify the areas, crime types, and time periods that require the most attention. This project analyzes crime data to identify important patterns that can help support better resource allocation and crime prevention.

---

## Objectives

The analysis answers the following questions:

- What are the most common types of crimes reported in Los Angeles?
- Which areas recorded the highest number of crime incidents?
- How did crime incidents change between 2020 and 2024?
- During which time of the day are crimes reported most frequently?
- How do crime incidents vary across different seasons?
- What are the most common crime types in the area with the highest number of reported incidents?

---

## Dataset

**Dataset:** Crime Data from 2020 to Present

The dataset contains:

- More than 1 million crime records
- 10 selected variables
- Crime information reported by the Los Angeles Police Department (LAPD)

Main columns used in this project include:

- Date Occurred
- Time Occurred
- Area Name
- Crime Code Description
- Report District
- Crime Classification

---

## Tools Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---

## Data Cleaning

The following data preparation steps were completed before the analysis:

- Checked for missing values
- Checked for duplicate records
- Extracted the Year from the occurrence date
- Extracted the Month from the occurrence date
- Created a Time of Day category
- Created a Season category
- Removed incomplete 2025 records from the yearly trend analysis

---

## Key Findings

The analysis showed that:

- Vehicle Theft was the most frequently reported crime.
- Central recorded the highest number of reported crime incidents.
- Crime incidents reached their highest level in 2022.
- Most crimes were reported during the Night.
- Crime incidents were higher during the Summer.
- Vehicle-related crimes were especially common in the Central area.

---

## Recommendations

Based on the findings, the following recommendations are suggested:

- Increase police patrols in high-crime areas, especially Central.
- Strengthen vehicle theft prevention and public awareness.
- Increase police presence during nighttime hours.
- Continue monitoring yearly crime trends to support future planning.

---

## Project Structure

```
Crime_Analysis_Los_Angeles/
│
├── README.md
├── Crime_Analysis_EDA.ipynb
├── Crime_Data_from_2020_to_Present-selected-columns.csv
├── Presentation.pdf
└── images/
```

---

## How to Run the Project

1. Clone or download this repository.
2. Open the Jupyter Notebook.
3. Make sure the dataset is in the same folder as the notebook.
4. Run all notebook cells from top to bottom.

---

## Author

**Fatima Awachi**

General Assembly Data Science Bootcamp
