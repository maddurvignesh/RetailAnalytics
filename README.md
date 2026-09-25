# Retail Analytics

An exploratory data analysis of customer responses to a retail marketing campaign. The project examines customer demographics, purchasing behavior, campaign engagement, and the factors associated with a successful response.

**Author:** `maddurvignesh`

## Project Overview

This repository contains a reproducible analysis of the Marketing Campaign dataset, which represents 2,240 customers and includes 27 demographic, behavioral, and campaign-related attributes.

The analysis is designed to:

- Understand the structure and quality of the dataset
- Explore numerical and categorical variables
- Summarize customer purchasing behavior
- Compare campaign-response outcomes across customer segments
- Identify relationships that may support future marketing decisions

## Dataset

| Property | Description |
| --- | --- |
| Records | 2,240 |
| Attributes | 27 |
| Primary outcome | `Response` |
| Source file | `marketing_campaign.csv` |

Key feature groups include:

- **Customer demographics:** age, education, marital status, and location
- **Customer behavior:** purchase frequency, monetary value, recency, and tenure
- **Campaign activity:** discount, promotion, and advertising channels
- **Engagement:** web, catalog, and store interactions
- **Response:** whether a customer accepted the campaign offer

`Metadata.csv` provides additional definitions for the dataset's core fields.

## Analysis

The notebook is organized into four main stages:

1. **General overview** — dataset shape, columns, data types, missing values, and duplicates
2. **Descriptive statistics** — summary measures, distributions, and value frequencies
3. **Univariate analysis** — histograms, box plots, and category-frequency analysis
4. **Bivariate analysis** — comparisons against `Response` using visualizations and chi-square tests

The bivariate section evaluates both numerical and categorical variables in relation to the campaign response, combining visual exploration with statistical testing.

## Tools and Libraries

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- SciPy

## Getting Started

### 1. Install dependencies

```bash
python -m pip install pandas numpy matplotlib scipy jupyter
```

### 2. Start Jupyter

```bash
jupyter lab
```

If JupyterLab is not available in your environment, run `jupyter notebook` instead.

### 3. Run the analysis

Open `analysis.ipynb` and execute the notebook cells from top to bottom.

## Project Structure

```text
RetailAnalytics/
├── analysis.ipynb             # Complete exploratory analysis
├── marketing_campaign.csv     # Customer and campaign dataset
├── Metadata.csv               # Core field definitions
└── README.md                  # Project documentation
```

## Key Files

- [`analysis.ipynb`](analysis.ipynb) — notebook containing data loading, exploratory analysis, visualizations, and statistical comparisons
- [`marketing_campaign.csv`](marketing_campaign.csv) — primary analysis dataset
- [`Metadata.csv`](Metadata.csv) — metadata for selected dataset columns

## Author

Created and maintained by **[maddurvignesh](https://github.com/maddurvignesh)**.
