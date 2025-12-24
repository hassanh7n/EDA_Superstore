# Superstore Dataset EDA

This repository contains an **Exploratory Data Analysis (EDA)** of a Superstore dataset. The goal is to uncover insights about sales, profit, customer segments, product categories, shipping, and regional performance.

---

## **Dataset Overview**
- **Records:** 9,994  
- **Columns:** Row ID, Order ID, Order Date, Ship Date, Ship Mode, Customer ID, Customer Name, Segment, Country, City, State, Postal Code, Region, Product ID, Category, Sub-Category, Product Name, Sales, Quantity, Discount, Profit  
- **Missing Values:** None  
- **Data Type:** Mixed (Numerical and Categorical)

---

## **Key Insights**

### **1. Customer Segment**
- **Dominant:** Consumer and Corporate  
- **Minor:** Home Office  
- **Takeaway:** Focus campaigns on Consumer and Corporate segments; Home Office is niche.

### **2. Product Categories**
- **Office Supplies:** Largest share, consistent profit  
- **Furniture:** High sales (~700k–800k) but low profit → margin issues  
- **Technology:** Highest sales and profit → key revenue driver  

### **3. Sub-Categories**
- **High Sales:** Phones, Chairs, Tables  
- **High Profit:** Copiers, Paper  
- **Observations:**  
  - Copiers → medium sales, highest profit  
  - Paper → low sales, very high profit  
  - Tables → high sales, negative profit  
  - Phones → high sales, second-highest profit  
  - Chairs → similar sales as phones but lower profit  

### **4. Shipping Mode**
- **Most common:** Standard Class  
- **Least common:** Same Day  

### **5. Regional Performance**
- **Top:** West  
- **Middle:** East  
- **Lowest:** South  

### **6. Sales & Profit**
- Both have **outliers**: few large orders dominate revenue  
- High discounts (70–80%) often lead to **profit losses**  
- Zero or small discounts yield **highest profits**

### **7. Correlations**
- Strong positive correlation between **Sales and Profit**  
- Weak negative correlation between **Quantity and Discount**  

---

## **Visualizations**
- Distribution of numerical features (Sales, Profit, Quantity, Discount)  
- Boxplots for outlier detection  
- Countplots for categorical features (Segment, Ship Mode, Category, Sub-Category, Region)  
- Correlation heatmap  
- Scatterplot of Profit vs Discount by Segment  
- Sales and Profit by Category, Sub-Category, and Segment  

---

## **Key Takeaways**
1. Furniture → high sales but low profit; requires pricing/discount review  
2. Copiers & Paper → medium sales, high profit; focus for profitability  
3. Extreme discounts → reduce profitability; moderate discounts recommended  
4. Consumer/Corporate segments and West/East regions drive most revenue  
5. Tables → high sales but negative profit; investigate costs  

---

