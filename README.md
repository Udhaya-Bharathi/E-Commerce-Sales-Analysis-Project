# E-Commerce Sales Analysis Project

## Project Overview
This project analyzes an **e-commerce sales dataset** to uncover key business insights, including sales trends, top products, and city-wise performance.  
The goal is to provide actionable recommendations to optimize **inventory, marketing, and sales strategies**.

**Dataset Size:** ~186,000 rows  
**Tools Used:** Python, Pandas, NumPy, Matplotlib, Seaborn  
**Type:** Exploratory Data Analysis (EDA) & Feature Engineering  

---

## Key Features & Steps

### 1. Data Cleaning
- Removed **duplicate headers** and invalid rows.  
- Converted numeric columns (`Quantity Ordered`, `Price Each`, `Order ID`) and `Order Date` to proper types.  
- Removed rows with missing or null values.  

### 2. Feature Engineering
- Created **`Sales = Quantity Ordered × Price Each`**  
- Extracted **time-based features:** Month, Month Name, Hour, Minute  
- Extracted **location-based features:** City, State, City/State Code  

### 3. Exploratory Data Analysis (EDA)
- **Monthly Sales Analysis:** Highest sales in **December**, lowest in **January**.  
- **City-Wise Sales:** San Francisco & Los Angeles generate highest revenue.  
- **Hourly Analysis:** Most orders between **7 PM and 11 PM**.  
- **Top Products:** USB-C Cables and AAA Batteries dominate in sales.  

### 4. Advanced Insights
- **Frequently Bought Together:** iPhone + Lightning Cable bundles identified for cross-selling.  
- **Price vs Quantity Analysis:** Higher-priced products sell less, indicating price sensitivity.  

---

## Key Insights & Recommendations
1. **Plan inventory and marketing campaigns** ahead of peak months (December).  
2. Focus logistics and promotions in **high-sales cities**: San Francisco & Los Angeles.  
3. Schedule **online promotions during peak purchase hours** (7 PM – 11 PM).  
4. Maintain stock for **best-selling products** like USB-C Cables and AAA Batteries.  
5. Offer **bundle promotions** for frequently bought together items.

---

## Skills Demonstrated
- Data Cleaning & Preprocessing  
- Feature Engineering  
- Exploratory Data Analysis (EDA)  
- Data Visualization (Matplotlib, Seaborn)  
- Market Basket Analysis  
- Python: Pandas, NumPy, Matplotlib, Seaborn  

---

## How to Run the Project
1. Clone the repository:  
```bash
git clone https://github.com/Udhaya-Bharathi/E-Commerce-Sales-Analysis-Project
