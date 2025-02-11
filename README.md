# 📊 Noise vs Residential Units Analysis

## Overview
**Noise vs Residential Units Analysis** is a data-driven project that explores the correlation between noise complaints and the number of residential units in different areas. Using Python and data visualization tools, this project analyzes relationships within a dataset to provide insights into urban noise patterns.

## 🚀 Features

### 📂 Data Handling
- Loads an Excel file containing noise complaint counts and residential unit totals.
- Cleans data by removing infinite values and NaNs.

### 📈 Statistical Analysis
- Computes the **Pearson correlation coefficient** to measure the strength of the relationship between noise and residential density.
- Displays the **p-value** to assess statistical significance.

### 📊 Visualization
- **Scatter Plot with Regression Line**: Shows the relationship between noise count and residential units.
- **Correlation Heatmap**: Provides an overview of correlations within the dataset.

## 🔧 Setup & Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/shahran-n/Property-Value-Correlation.git
   ```
2. Navigate to the project directory:
   ```sh
   cd Property-Value-Correlation
   ```
3. Install dependencies:
   ```sh
   pip install pandas seaborn matplotlib scipy openpyxl
   ```
4. Run the analysis script:
   ```sh
   python main.py
   ```

## 🏗️ How It Works
1. **Load Data**: The script loads an Excel dataset (`sales_andnoise_byCT.xlsx`) with noise counts and residential unit data.
2. **Data Cleaning**: Handles missing or infinite values to ensure accurate analysis.
3. **Correlation Calculation**: Computes the Pearson correlation coefficient and p-value.
4. **Visualization**:
   - Generates a scatter plot with a regression line to illustrate trends.
   - Creates a correlation heatmap to show relationships between variables.

## 📌 Use Cases
- **Urban Planning**: Helps city planners understand how residential density affects noise complaints.
- **Environmental Studies**: Provides data for noise pollution analysis.
- **Real Estate**: Insights into noise levels for property assessments.

## 📌 Technologies Used
- **Python**
- **Pandas**
- **Seaborn & Matplotlib**
- **SciPy**
