**1. Measure: Total Sales Amount**  
- **DAX Expression:** SUM('Sales'[Sales Amount])  
- **Description:**  
  This measure calculates the sum of the Sales Amount column in the Sales table. It aggregates (adds up) all sales amount values for the context defined by your filters (such as date, product, customer, etc.). Use this measure to quickly see total revenue or sales amount for any slice of your data.

---

**2. Measure: Total Order Quantity**  
- **DAX Expression:** SUM('Sales'[Order Quantity])  
- **Description:**  
  This measure adds up all the values of the Order Quantity column in the Sales table. It tells you the total number of items or units ordered in your dataset for the applied context. Use it to analyze how many products were sold or ordered across any dimension such as time, geography, or product category.

---

**3. Measure: Total Product Costs**  
- **DAX Expression:** SUM('Sales'[Total Product Cost])  
- **Description:**  
  This measure computes the total product costs by summing the values in the Total Product Cost column from the Sales table. It gives you the overall cost incurred for products sold in your chosen data subset. It’s useful for profitability analysis and understanding cost patterns over time or across different business segments.

---

All three measures use the DAX SUM function, meaning they simply aggregate their target numeric column for the current filter context in your reports or visuals, responding dynamically to your slicers and filters.