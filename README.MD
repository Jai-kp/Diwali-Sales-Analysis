# EDA Project: Diwali Sales Analysis

## Overview
This project explores and analyzes Diwali sales data using Python, pandas, matplotlib, and seaborn. The analysis covers demographics, purchasing power, product categories, and key insights to help understand customer behavior and business opportunities during the Diwali festival sales period.

## Dataset
- **File**: `Diwali Sales Data.csv`
- **Rows**: 11,251
- **Columns**: 15 (after cleaning: 13)
- **Features**: User_ID, Cust_name, Product_ID, Gender, Age Group, Age, Marital_Status, State, Zone, Occupation, Product_Category, Orders, Amount

## Analysis Steps
1. **Data Loading & Inspection**: Read the dataset, inspect for basic properties and data types.
2. **Cleaning**:
   - Dropped irrelevant columns: `Status`, `unnamed1`
   - Removed rows with missing values in `Amount`
   - Converted `Amount` to `int` type for analysis
3. **EDA**:
   - Gender-wise purchase counts and amount analysis
   - Age group distribution and their purchasing power
   - State-wise top orders and sales
   - Analysis of marital status and purchasing trends
   - Occupation distribution among buyers
   - Top product categories and products

## Key EDA Insights
### Gender
- Most buyers are females, who also have higher purchasing power than males.

### Age Group
- The 26-35 age group (especially females) forms the largest customer segment.

### State
- Top contributing states: Uttar Pradesh, Maharashtra, and Karnataka.
- These states lead both in number of orders and total sales.

### Marital Status
- Married women are more likely to buy and contribute more to sales.

### Occupation
- IT, Healthcare, and Aviation sector professionals are the top buyers.

### Product Category
- Most sold: Food, Footwear, and Electronics categories.
- Inventory optimization in these categories can improve sales further.

### Conclusion & Business Outcomes
- **Target Segment**: Married women (25-35 years) from Uttar Pradesh, Maharashtra, and Karnataka, especially in IT, Healthcare, and Aviation, are prime customers.
- **Sales Strategy**: Focus marketing and inventory planning on Food, Clothing, and Electronics.

## Libraries Used
- pandas
- numpy
- matplotlib
- seaborn

## How to Reproduce
1. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
2. Run the notebook: `EDA_Diwali Sales Analysis.ipynb`

