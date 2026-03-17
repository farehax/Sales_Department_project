# Sales Department Project

![GitHub repo size](https://img.shields.io/github/repo-size/farehax/Sales_Department_project)
![GitHub stars](https://img.shields.io/github/stars/farehax/Sales_Department_project?style=social)
![GitHub forks](https://img.shields.io/github/forks/farehax/Sales_Department_project?style=social)
![Python](https://img.shields.io/badge/Python-3.10-blue)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

## 📌 Overview
This project focuses on analyzing sales data to uncover insights that can enhance sales strategies and performance

## ⭐ Key Highlights

- Performed complete **EDA on sales dataset**
- Built a **sales prediction model**
- Achieved improved model performance
- Visualized trends using **Matplotlib & Seaborn**
- Analyzed impact of **holidays & external factors**

## 📂 Project Structure

```
├── Sales_Department_Png/             # Visualizations generated during analysis
├── store.csv                         # Dataset containing store information
├── train.csv                         # Dataset containing sales transaction records
├── Sales_Department_Project.ipynb    # Jupyter Notebook with analysis and findings
├── README.md                         # Project documentation
```

## 📊 Dataset

The project utilizes two primary datasets:

1. **store.csv*: Contains information about different stores, includig:
   - **Store ID*: Unique identifier for each stoe.
   - **Type*: Categorical variable indicating the type of stoe.
   - **Size*: The physical size of the stoe.

2. **train.csv*: Includes historical sales data with features such s:
   - **Store ID*: Reference to the stoe.
   - **Date*: The date of the sales recod.
   - **Weekly Sales*: Sales figures for the given wek.
   - **Holiday Flag*: Indicator of whether the week includes a holidy.
   - **Temperature*: Average temperature for the wek.
   - **Fuel Price*: Cost of fuel during the wek.
   - **CPI*: Consumer Price Indx.
   - **Unemployment*: Unemployment rate during the wek.

## 🚀 Installation

### 1️⃣ Clone the repository:

```bash
git clone https://github.com/farehax/Sales_Department_project.git
cd Sales_Department_project
```

### 2️⃣ Install dependencies:

Ensure you have the following Python packages installed:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

You can install them using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 🔍 Methodology

### 1. **Data Preprocessing**

- **Handling Missing Value**: Identified and addressed any missing data in the dataets.
- **Feature Engineerin**: Created new features to better capture temporal patterns, such as extracting month and year from the `Date` feld.
- **Data Mergin**: Combined `store.csv` and `train.csv` datasets based on `Store ID` to consolidate informaion.

### 2. **Exploratory Data Analysis (EDA)**

- **Sales Trends Analysi**: Examined sales patterns over time to identify seasonal effects and trnds.
- **Impact of Holiday**: Analyzed how holidays influence weekly sales figres.
- **Correlation Analysi**: Explored relationships between sales and external factors like `Temperature`, `Fuel Price`, `CPI`, and `Unemploymnt`.

### 3. **Predictive Modeling**

- **Sales Forecastin**: Developed regression models to predict future sales based on historical data and external variales.
- **Model Evaluatio**: Assessed model performance using metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RSE).

## 📊 Visualizations
![Group by Month Customer](https://github.com/farehax/Sales_Department_project/blob/main/Sales%20Department%20Project%20Png/groupby%20month%20customer.png)

![Group by Month](https://github.com/farehax/Sales_Department_project/blob/main/Sales%20Department%20Project%20Png/groupby%20month.png)

![Heatmap](https://github.com/farehax/Sales_Department_project/blob/main/Sales%20Department%20Project%20Png/heatmap.png)

![Sales Predictions](https://github.com/farehax/Sales_Department_project/blob/main/Sales%20Department%20Project%20Png/sales_predictions.png)

![Sales Histogram](https://github.com/farehax/Sales_Department_project/blob/main/Sales%20Department%20Project%20Png/sales_train_df_hist.png)

![Store Info Histogram](https://github.com/farehax/Sales_Department_project/blob/main/Sales%20Department%20Project%20Png/store_info_df.hist.png)

## 🛠️ Technologies Used

- **Python**
- **Pandas & NumPy**
- **Matplotlib & Seaborn**
- **Scikit-learn**
- **Jupyter Notebook**

## 📌 Future Improvements

- **Advanced Time Series Moels**: Implement models like ARIMA or Prophet for more accurate sales foreasting.
- **Incorporate Additional ata**: Integrate external data sources such as economic indicators or competitor pricing to enhance model perfrmance.
- **Interactive Dashbords**: Develop dashboards using tools like Tableau or Power BI for real-time sales monitoring and decision upport.

 ## 🙋‍♀️ Author

**Fareha Khan**

📫 Connect with me on LinkedIn

