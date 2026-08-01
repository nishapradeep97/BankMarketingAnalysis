# 📊 Bank Marketing Data Analysis

## 📌 Project Overview

The **Bank Marketing Data Analysis** project performs an end-to-end **Exploratory Data Analysis (EDA)** on the **Bank Marketing Dataset** using **Python** in **Jupyter Notebook**. The dataset contains information collected during direct marketing campaigns conducted by a Portuguese banking institution. The objective is to analyze customer demographics, campaign performance, financial characteristics, and economic indicators to understand the factors influencing whether a customer subscribes to a **term deposit**.

This project demonstrates a complete data analytics workflow, including **data preprocessing, feature engineering, exploratory data analysis (EDA), statistical analysis, and data visualization** to derive meaningful business insights.

---

## 🎯 Objectives

- Analyze customer demographics and financial characteristics.
- Evaluate the effectiveness of marketing campaigns.
- Identify factors influencing term deposit subscriptions.
- Perform univariate, bivariate, and multivariate analysis.
- Analyze relationships between variables using statistical methods.
- Generate business insights through visualization.

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Dataset

**Source:** UCI Machine Learning Repository

**Dataset File:**

`Bank Marketing Data.csv`

The dataset contains customer demographic information, financial details, campaign interactions, previous campaign outcomes, economic indicators, and the subscription status (target variable).

### Key Features

- Age
- Job
- Marital Status
- Education
- Credit in Default
- Housing Loan
- Personal Loan
- Contact Method
- Month
- Day of Week
- Campaign Duration
- Campaign Contacts
- Previous Campaign Outcome
- Employment Variation Rate
- Consumer Price Index
- Consumer Confidence Index
- Euribor 3-Month Rate
- Number of Employees
- Subscription Status

---

## 🧹 Data Preprocessing

The following preprocessing steps were performed:

- Loaded the dataset into a Pandas DataFrame.
- Checked dataset dimensions and structure.
- Renamed columns for better readability.
- Verified data types.
- Checked missing values.
- Removed duplicate records.
- Standardized categorical values.
- Replaced **unknown** values with **missing**.
- Created new features:
  - Age Group
  - Campaign Type
- Verified unique values.

---

## 📊 Exploratory Data Analysis

The project includes:

- Dataset Overview
- Statistical Summary
- Missing Value Analysis
- Duplicate Analysis
- Unique Value Analysis
- Feature Engineering
- Univariate Analysis
- Bivariate Analysis
- Multivariate Analysis
- Correlation Analysis
- Pivot Tables
- Grouping & Aggregation

---

## 📈 Visualizations

The notebook contains the following visualizations:

- 📊 Bar Plot
- 🥧 Pie Chart
- 📉 Histogram
- 📦 Box Plot
- 🔵 Scatter Plot
- 🔥 Correlation Heatmap
- 📈 Line Chart
- 🎻 Violin Plot
- 📋 Subplots
- 🐝 Swarm Plot
- 📊 Count Plot
**📷 Project Visualizations**

**📊 Dataset Overview**

Displays the structure, dimensions, and summary of the Bank Marketing dataset.
<img width="1515" height="231" alt="image" src="https://github.com/user-attachments/assets/5d1b3c66-5fc7-4ce9-9fac-3d8520329b4f" />

**📊 Bar Plot**

Bar chart showing the number of customers across different occupations.
<img width="1167" height="670" alt="image" src="https://github.com/user-attachments/assets/e04f85ca-4c00-44aa-b526-a56a658bfdf0" />


**🥧 Pie Chart**

Pie chart illustrating the proportion of customers who subscribed and did not subscribe to the term deposit.
<img width="747" height="625" alt="Screenshot 2026-08-01 094446" src="https://github.com/user-attachments/assets/387e2efc-c38c-472f-9afb-de20cedb2866" />


**📉 Histogram**

Histogram showing the distribution of customer ages.
<img width="1086" height="585" alt="image" src="https://github.com/user-attachments/assets/1a8ad2f7-803a-4bd3-b331-4c04951487d3" />

**📦 Box Plot**

Box plot illustrating the spread of campaign call durations and identifying potential outliers.
<img width="835" height="442" alt="image" src="https://github.com/user-attachments/assets/6b288a39-197d-4c5a-98b8-60b82c62b06c" />

**🔵 Scatter Plot**

Scatter plot showing the relationship between customer age and campaign duration.
<img width="990" height="597" alt="image" src="https://github.com/user-attachments/assets/cdf0f8c8-8d4b-460a-b302-b16e40d410e9" />

**🔥 Correlation Heatmap**

Heatmap displaying correlations among numerical variables.
<img width="917" height="720" alt="image" src="https://github.com/user-attachments/assets/9cada11a-7b83-4d09-8cd2-4674cfe4adb1" />


**📈 Line Chart**

Line chart showing monthly variations in average campaign duration.
<img width="867" height="391" alt="image" src="https://github.com/user-attachments/assets/1666d486-58f7-4225-bc87-839ed933be20" />


**Sub Plots**

Displays multiple visualizations in a single figure to compare relationships between customer attributes and campaign performance, making it easier to identify patterns and trends.
<img width="937" height="325" alt="image" src="https://github.com/user-attachments/assets/2606aa7c-6ab5-440b-89fe-4724e181bd64" />


**🎻 Violin Plot**

Violin plot illustrating the distribution of campaign duration based on subscription status.
<img width="731" height="390" alt="image" src="https://github.com/user-attachments/assets/b6b202c7-8842-4eda-9557-229bd96fd2ca" />

**🐝Swarm Plot**

Swarm plot comparing customer ages for subscribed and non-subscribed customers.
<img width="912" height="402" alt="image" src="https://github.com/user-attachments/assets/67eee5f7-601d-49bf-bafa-bc140000351d" />

**📊Count Plot**

Count plot comparing subscription outcomes across education levels.
<img width="915" height="417" alt="image" src="https://github.com/user-attachments/assets/bfb10cc2-ed1f-4fd2-9b7b-18465139b803" />

**🔍 Key Insights**

Most customers did not subscribe to the term deposit.

Adult and Middle Age customers represent the majority of the customer base.

Customer demographics vary across education and occupation.

Campaign duration differs between subscribed and non-subscribed customers.

Multiple campaign contacts influence customer engagement.

Most numerical variables exhibit weak to moderate correlations.

Customer subscription decisions are influenced by demographic, campaign, and economic factors.

**📁 Repository Structure**

```text
BankMarketingAnalysis/
│
├── 📂 Data/
│   └── Bank Marketing Data.csv
│
├── 📂 Notebook/
│   └── Bank Marketing Analysis.ipynb
│
├── 📂 Images/
│   ├── dataset_overview.png
│   ├── bar_plot.png
│   ├── pie_chart.png
│   ├── histogram.png
│   ├── box_plot.png
│   ├── scatter_plot.png
│   ├── heatmap.png
│   ├── line_chart.png
│   ├── violin_plot.png
│   ├── swarm_plot.png
│   ├── count_plot.png
│   └── subplot.png
│
├── README.md
└── requirements.txt
```

# 🚀 How to Run

Follow these steps to run the project on your local machine.

### 1️⃣ Clone the repository

```bash
git clone https://github.com/nishapradeep97/BankMarketingAnalysis.git
```

### 2️⃣ Navigate to the project folder

```bash
cd BankMarketingAnalysis
```

### 3️⃣ Install the required libraries

```bash
pip install -r requirements.txt
```

### 4️⃣ Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5️⃣ Open the notebook

```text
Bank Marketing Analysis.ipynb
```

### 6️⃣ Run the project

Run all notebook cells sequentially to reproduce the complete data cleaning, preprocessing, exploratory data analysis (EDA), statistical analysis, and visualizations.

**📌 Conclusion**

This project demonstrates a complete data analytics workflow using Python, from data preprocessing to insight generation. The findings help understand customer behavior, evaluate marketing campaign effectiveness, and support data-driven decision-making. The analysis can assist banks in improving customer segmentation, optimizing marketing strategies, and increasing the effectiveness of future term deposit campaigns.

**👩‍💻 Author**

Nisha Pradeep

GitHub: https://github.com/nishapradeep97/
