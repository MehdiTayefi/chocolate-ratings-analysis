# Chocolate Ratings Analysis

## Project Overview

This project performs an exploratory data analysis (EDA) on a chocolate
ratings dataset.

The goal is to understand patterns in chocolate reviews, including:

- rating distributions
- cocoa percentage patterns
- relationships between cocoa percentage and ratings
- company performance
- review activity over time
- bean origins and types

The project demonstrates a complete data analysis workflow: from data
exploration and cleaning to exploratory analysis and insight generation.

------------------------------------------------------------------------

## Dataset

The dataset used in this project was provided as part of an educational
data analysis course.

It contains information about chocolate reviews, including:

- company
- review date
- cocoa percentage
- rating
- company location
- bean type
- bean origin

The dataset is used for educational and analytical purposes.

------------------------------------------------------------------------

## Project Structure

    chocolate-ratings-analysis/

    ├── data/
    │   ├── raw/
    │   │   └── chocolate.csv
    │   │
    │   └── processed/
    │       └── chocolate_clean.csv
    │
    ├── notebooks/
    │   ├── 01_data_exploration.ipynb
    │   ├── 02_data_cleaning.ipynb
    │   └── 03_exploratory_data_analysis.ipynb
    │
    ├── README.md
    ├── requirements.txt
    └── .gitignore

------------------------------------------------------------------------

## Analysis Workflow

### 1. Data Exploration

Initial inspection of:

- dataset structure
- columns
- missing values
- data types

### 2. Data Cleaning

The cleaning process included:

- handling missing values
- standardizing text columns
- converting cocoa percentage values
- removing duplicate records
- preparing a clean dataset for analysis

### 3. Exploratory Data Analysis

The analysis investigated:

- rating distribution
- cocoa percentage distribution
- cocoa percentage vs rating relationship
- yearly review trends
- company ratings
- company locations
- bean origins

------------------------------------------------------------------------

## Key Findings

- The dataset contains approximately 1,795 chocolate reviews.
- The average rating is around 3.19.
- 70% cocoa content is the most common cocoa percentage in reviewed
    chocolates.
- Cocoa percentage shows a weak relationship with rating.
- Company comparisons should consider the number of reviews because
    sample sizes differ.
- The dataset represents reviewed chocolates and should not be
    interpreted as a complete representation of the global chocolate
    market.

------------------------------------------------------------------------

## Technologies Used

Python

Libraries:

- pandas
- numpy
- matplotlib
- seaborn
- Jupyter Notebook

------------------------------------------------------------------------

## How to Run

Clone the repository:

` bash
git clone <repository-url>
`

Install dependencies:

` bash
pip install -r requirements.txt
`

Open Jupyter Notebook:

` bash
jupyter notebook
`

Run notebooks in order:

1. Data Exploration
2. Data Cleaning
3. Exploratory Data Analysis

------------------------------------------------------------------------

## Limitations

- The dataset represents reviewed chocolates rather than all
    chocolates worldwide.
- Differences between companies may be affected by unequal review
    counts.
- Correlation analysis does not prove causal relationships.
- Some categorical labels contain broad or combined categories.

------------------------------------------------------------------------

## Future Improvements

Possible extensions:

- build a rating prediction model
- analyze text reviews if available
- compare companies with statistical methods
- create an interactive dashboard
