# AI-Powered Customer Segmentation Dashboard

An end-to-end customer segmentation project that transforms customer data into actionable insights using data preprocessing, exploratory data analysis, RFM-based segmentation, K-Means clustering, and an interactive Streamlit dashboard.

## Project Overview

This project analyzes customer purchasing behavior and demographic characteristics to identify meaningful customer segments.

The project covers the complete workflow:

**Data Preparation → EDA → Customer Segmentation → Interactive Dashboard**

## Key Features

* Data cleaning and preprocessing
* Missing value and duplicate handling
* Feature engineering including Age Groups and Total Spent
* Exploratory Data Analysis using Pandas, Matplotlib and Seaborn
* Customer segmentation using RFM metrics:
  * Recency
  * Frequency
  * Monetary Value
* K-Means clustering for customer segmentation
* Interactive Streamlit dashboard
* Dynamic filtering by:
  * Age Group
  * Gender
  * Income Bracket
* Interactive Plotly visualizations
* Key customer metrics and filtered customer data

## Dashboard
The Streamlit application provides an interactive interface where users can filter customers and explore:

* Customer count
* Total spending
* Average order value
* Age group distribution
* Gender distribution
* Income bracket distribution

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Plotly
* Streamlit
* Joblib

## Project Structure

```text
AI-Customer-Segmentation/
│
├── BharatCart_Project-new.ipynb
├── BharatCart_Ecommerce_Dataset.csv
├── customer_segmentation_ui.py
├── customer_data_df.joblib
├── kmeans_model.pkl
├── requirements.txt
└── README.md
```

## How to Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/harshasrivastav1/AI-Customer-Segmentation.git
cd AI-Customer-Segmentation
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Streamlit application

```bash
streamlit run customer_segmentation_ui.py
```

## Live Demo

**Streamlit App:**
(https://harsha-customer-segmentation.streamlit.app/)

## Project Objective

The objective of this project is to use customer transaction and demographic data to identify distinct customer groups and provide an interactive analytical interface for exploring customer behavior.

## Author

**Harsha Srivastav**


