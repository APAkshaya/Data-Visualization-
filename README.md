# Restaurant Sales Prediction and Analysis

### Data Visualization Techniques Lab

This project analyzes **Restaurant Sales Data** using Python-based data processing, exploratory data analysis (EDA), preprocessing techniques, statistical analysis, data visualization, and machine learning.

---

## Dataset

**Dataset:** Restaurant Sales Dataset

The dataset contains information related to restaurant sales, food items, quantities sold, prices, and revenue. The data is used to analyze sales patterns and predict future restaurant sales.

### Dataset Attributes

The dataset may include attributes such as:

- Date
- Food Item
- Category
- Quantity Sold
- Unit Price
- Total Sales
- Revenue
- Day
- Month

The **Total Sales / Revenue** column is used as the target variable for sales prediction.

---

## Project Objective

The objective of this project is to analyze restaurant sales data, perform data preprocessing, explore sales patterns, calculate statistical measures, apply grouping and aggregation, perform correlation analysis, create meaningful visualizations, and predict future restaurant sales using machine learning.

The project demonstrates how data analysis and visualization techniques can be used to understand:

- Overall restaurant sales
- Daily and monthly sales trends
- Best-selling food items
- Sales by food category
- Revenue generated
- Quantity of items sold
- High and low performing products
- Relationships between sales-related variables
- Future sales prediction

---

## Experiments

### Experiment 1 — Restaurant Sales Prediction Using Machine Learning

**Aim:** To analyze restaurant sales data, identify important sales patterns, build a machine learning model to predict sales, evaluate the model, and visualize the results.

**Work Performed:**

- Dataset loading and inspection
- Dataset shape and information analysis
- Missing-value detection
- Data cleaning
- Duplicate-record detection
- Date and time processing
- Feature selection
- Encoding categorical variables
- Train-test splitting
- Machine learning model training
- Sales prediction
- Model evaluation
- Visualization of actual and predicted sales

**Model:** Random Forest Regression

**Target Variable:** `Total Sales`

**Outcome:** A machine learning model was trained to predict restaurant sales based on historical sales information.

---

### Experiment 2 — EDA – Data Cleaning

**Aim:** To clean the Restaurant Sales dataset by detecting and handling missing values, duplicate records, incorrect data types, and unnecessary data.

**Work Performed:**

- Identification of missing values
- Handling missing values
- Duplicate-record detection
- Removal of duplicate records
- Data-type inspection
- Date conversion
- Removal of unnecessary columns
- Data transformation
- Display of cleaned data

**Outcome:** The dataset was successfully cleaned and prepared for further analysis.

---

### Experiment 3 — EDA – Data Inspection and Analysis

**Aim:** To inspect and analyze the Restaurant Sales dataset using DataFrame operations, conditional filtering, descriptive statistics, and measures of central tendency and dispersion.

**Work Performed:**

- Viewing the first five records
- Viewing the last five records
- Inspecting dataset shape
- Inspecting column names
- Checking data types
- Filtering high-sales records
- Filtering food items
- Selecting specific columns
- Calculating mean
- Calculating median
- Calculating mode
- Calculating range
- Calculating variance
- Calculating standard deviation
- Generating descriptive statistics

**Outcome:** The experiment provides statistical insights into restaurant sales and food-item performance.

---

### Experiment 4 — Data Visualization

**Aim:** To visualize restaurant sales data using Python by creating bar charts, pie charts, histograms, and line charts.

**Visualizations:**

- **Bar Chart:** Sales by food item
- **Pie Chart:** Sales by food category
- **Line Chart:** Sales trend over time
- **Histogram:** Distribution of sales
- **Scatter Plot:** Quantity sold vs revenue

**Outcome:** The visualizations provide an intuitive understanding of restaurant sales patterns and product performance.

---

### Experiment 5 — Calculated Field and Data Visualization

**Aim:** To create calculated fields from restaurant sales data and visualize the resulting information.

**Work Performed:**

A calculated field named **Sales Category** was created to classify sales into categories such as:

- High Sales
- Medium Sales
- Low Sales

**Visualizations:**

- Bar Chart: Sales category distribution
- Line Chart: Sales trend
- Pie Chart: Sales by category

**Outcome:** The calculated fields and visualizations provide a clearer understanding of restaurant sales performance.

---

### Experiment 6 — EDA – Grouping and Aggregation

**Aim:** To perform grouping and aggregation on the Restaurant Sales dataset using Pandas.

**Work Performed:**

- Grouping sales by food item
- Calculation of total sales by food item
- Calculation of average sales
- Calculation of total quantity sold
- Grouping sales by category
- Calculation of total revenue by category
- Analysis of daily sales
- Analysis of monthly sales
- Bar-chart visualization of sales

**Outcome:** The grouping and aggregation analysis identifies high-performing food items and categories.

---

### Experiment 7 — EDA – Correlation Analysis

**Aim:** To analyze relationships between numerical variables in the Restaurant Sales dataset using correlation analysis and a heatmap.

**Numerical attributes analyzed:**

- Quantity Sold
- Unit Price
- Total Sales
- Revenue

A correlation matrix was calculated and visualized using a heatmap.

**Visualization:** Correlation Heatmap

**Outcome:** The correlation analysis provides an understanding of relationships between sales-related numerical variables.

---

## How This Project Aligns with Data Visualization

### 1. Comparison

Bar charts are used to compare:

- Sales across food items
- Sales across categories
- Revenue generated by products
- Quantity sold

### 2. Trends

Line charts are used to visualize:

- Daily sales
- Monthly sales
- Sales trends over time

### 3. Distribution

Pie charts and histograms are used to represent:

- Sales by category
- Distribution of sales
- Product contribution to total sales

### 4. Relationships

Scatter plots are used to study relationships such as:

- Quantity sold vs total sales
- Unit price vs revenue
- Sales vs quantity

### 5. Correlation

A correlation heatmap is used to show relationships between numerical variables such as:

- Quantity Sold
- Unit Price
- Total Sales
- Revenue

### 6. Statistical Analysis

Mean, median, mode, range, variance, standard deviation, and descriptive statistics are used to understand restaurant sales data.

### 7. Multivariate Analysis

Multiple sales-related attributes are analyzed together to understand factors affecting restaurant performance.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab
- Excel
- GitHub

---

## Machine Learning

The project includes a machine-learning regression model for restaurant sales prediction.

**Algorithm Used:** Random Forest Regression

**Target Variable:** `Total Sales`

The model uses historical restaurant sales information to predict future sales.

### Evaluation Metrics

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## Dataset Information

The Restaurant Sales dataset contains historical information about restaurant transactions and sales performance.

### Attributes

| Attribute | Description |
|---|---|
| Date | Date of the transaction |
| Food Item | Name of the food item |
| Category | Food category |
| Quantity Sold | Number of items sold |
| Unit Price | Price of one item |
| Total Sales | Total sales generated |
| Revenue | Revenue generated |
| Day | Day of the transaction |
| Month | Month of the transaction |

