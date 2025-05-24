# 🏡 House Prices Analysis

A data science project focused on **cleaning, processing, and analyzing housing price data** to uncover key insights and patterns. This project showcases a complete data pipeline from raw data ingestion to exploratory data analysis using Python and Jupyter Notebooks.

---

## 📁 Project Structure

```mermaid
flowchart TD
    A[📄 Raw Data[house_prices.csv] --> B[🧹 Data Cleaning-->[Data_clean.ipynb]
    B --> C[📄 Cleaned Data<br>house_prices_cleaned.csv]
    C --> D[📊 Data Analysis[Analysis.ipynb]
```
## 📌Objectives
Perform data cleaning and preprocessing on raw housing data.

Conduct exploratory data analysis (EDA) to understand key variables.

Identify factors influencing house prices using statistical methods and visualization.

## 🚀 Getting Started
### 1. Clone the Repository
```
   git clone https://github.com/Omkararora-atc/house-prices-analysis.git
   cd house-prices-analysis
```
### 2. Install Dependencies
Option A: Using requirements.txt
```
pip install -r requirements.txt
```
Option B: Manual Installation
```
pip install pandas numpy matplotlib seaborn jupyter
```
### 3. Run the Notebooks
```
jupyter notebook
```
**Recommended execution order:**

* **Data_clean.ipynb** – cleans and preprocesses the raw dataset.

* **Analysis.ipynb** – performs data visualization and insights extraction.

## 📊 Dataset Overview
* **Source**: house_prices.csv

* **Features**: Includes variables such as lot size, number of bedrooms, bathrooms, garage capacity, and sale price.

* **Target**: Sale Price (SalePrice)

## 📈 Sample Insights

* Correlations between sale price and features such as living area and number of garages.

* Outlier detection and handling strategies.

* Visual trends across different neighborhoods and property types.

## 📄 Files Description

```
| File                       | Description                                   |
| -------------------------- | --------------------------------------------- |
| `house_prices.csv`         | Original raw dataset                          |
| `Data_clean.ipynb`         | Notebook for data cleaning and transformation |
| `house_prices_cleaned.csv` | Output after cleaning                         |
| `Analysis.ipynb`           | Analysis and visualization notebook           |
```
## 📜 License
This project is licensed under the MIT License. See the LICENSE file for details.

## 👤 Author
Omkar Arora

Linkedin:-[OmkarArora](https://www.linkedin.com/in/omkar-arora-7397b9339/)