# **Sales Analysis Dashboard in Excel**

## **Table of Contents**
1. [Introduction](#introduction)  
2. [Features](#features)  
3. [Data Cleaning and Transformation](#data-cleaning-and-transformation)  
4. [Pivot Table Analysis](#pivot-table-analysis)  
5. [Visualizations](#visualizations)  
6. [Dashboard Design](#dashboard-design)  
7. [Insights](#insights)  
8. [How to Use the Project](#how-to-use-the-project)  
9. [Skills Demonstrated](#skills-demonstrated)  

---

## **1. Introduction**
The Sales Analysis Dashboard project demonstrates advanced **data analytics** and **visualization** capabilities using Excel.  
It combines **Power Query**, **Pivot Tables**, and **Charts** to derive actionable insights from raw sales data.  
The final output is an interactive **dashboard** where users can dynamically filter and explore data for decision-making.

---

## **2. Features**
- **Dynamic Slicers** for gender, channels, states, and more.
- **Interactive Dashboard** allowing responsive filtering across all visualizations.
- Insights derived from data analysis to answer key business questions like:
  - Which channels contribute the most to sales?
  - Which age group generates maximum orders?
  - What are the sales trends over time?

---

## **3. Data Cleaning and Transformation**
### **Steps in Power Query**
1. **Import Dataset**: Open the raw dataset in Power Query for preprocessing.
2. **Text Transformation**: Converted non-numeric entries in `Qty` (e.g., "One", "Two") to numeric values (1, 2).  
   - Formula Example: `if [Qty] = "One" then 1 else if [Qty] = "Two" then 2 else [Qty]`
3. **Gender Standardization**: Standardized inconsistent gender entries like "M" → "Men" and "F" → "Women".
4. **Data Types**: Ensured columns were set to the correct data types (e.g., date, text, or number).
5. **Load Clean Data**: Loaded the cleaned data back into Excel for analysis.

  ![Data cleaning](https://github.com/user-attachments/assets/f2d09811-8e48-4de1-894e-b87de14f17a5)
---

## **4. Pivot Table Analysis**
### **Key Questions Answered**
Using Pivot Tables, the following analyses were performed:

| **Question**                           | **Method**                                                                                  | **Findings**                                                                 |
|----------------------------------------|--------------------------------------------------------------------------------------------|------------------------------------------------------------------------------|
| Compare sales and orders               | Analyzed sales vs. orders trends in one chart.                                              | Monthly trend identified.                                                    |
| Highest sales month                    | Filtered by months.                                                                         | **March** had the highest sales and orders.                                  |
| Gender-based sales contribution        | Filtered sales data by gender.                                                              | Women contributed **69%** of total sales; men contributed **31%**.           |
| Top 10 states contributing to sales    | Filtered sales by `State` and ranked using value filters.                                   | Top states: **Maharashtra, Karnataka, Uttar Pradesh, Tamil Nadu, Telangana**.|
| Relationship between age and gender    | Created a pivot using `Age` and `Gender` dimensions.                                        | 70% of sales come from age group **18-44**.                                  |
| Sales by channels                      | Filtered data by channels and ranked sales contribution.                                    | Top 3 channels: **Amazon, Myntra, Flipkart**, accounting for **80% of sales**.|
| Highest-selling categories             | Filtered data by product categories.                                                       | Top categories: **Kurta**, **Set**.                                          |

![Pivot table](https://github.com/user-attachments/assets/3bb3bbb8-807b-436b-a099-b9db519d0996)

---

## **5. Visualizations**
### **Key Charts**
1. **Sales vs. Orders Chart**  
   - Monthly trend chart comparing sales and orders.
   - Includes a dual-axis for easy comparison.

2. **Gender-Based Sales Contribution**  
   - Pie chart showcasing sales contribution of men and women.  
   - Women: 69% | Men: 31%.

3. **Top States by Sales**  
   - Horizontal bar chart ranking the top 5 states contributing to sales.

4. **Age and Gender Orders Analysis**  
   - Stacked bar chart analyzing sales by age groups and gender.

5. **Channel Sales Contribution**  
   - Column chart highlighting sales contributions by channels.

6. **Highest-Selling Categories**  
   - Bar chart ranking top-selling categories.
---

## **6. Dashboard Design**
### **Steps to Create the Dashboard**
1. **Combine Charts**: Integrated all charts into a single worksheet.
2. **Add Slicers**:  
   - Slicers for filtering charts by:
     - Gender
     - Sales Channel
     - Product Category
     - State
     - Month
3. **Connect Slicers**: Linked slicers to all charts for seamless filtering.
4. **Finalize Layout**: Arranged charts for a professional and user-friendly design.

![dashboard](https://github.com/user-attachments/assets/17f69dc3-7b2d-47bc-b876-a3586b24b48e)


---

## **7. Insights**

### **Gender-Based Insights**
- **Women**:  
  - Contribute **69% of total sales**.  
  - Prefer shopping on **Amazon, Myntra, and Flipkart**, making up **80% of orders**.  
  - Key product preferences: **Kurta** and **Set** (80% of women's sales).  
  - **18 to 44 years** accounts for **70% of women's sales**.  
  - Top states: **Maharashtra, Karnataka, Uttar Pradesh, Tamil Nadu, Telangana**.  

- **Men**:  
  - Contribute **31% of total sales**.  
  - Prefer shopping on the same channels as women.  
  - Key product preferences: **Set** and **Western Dress** (91% of men's sales).  
  - **25 to 34 years** accounts for **60% of men's sales**.

### **Channel Insights**
- **Amazon**, **Myntra**, and **Flipkart** are the top-performing sales channels.  
- Combined, these platforms contribute **80% of total sales**.

### **Time-Based Insights**
- **March** is the month with the **highest sales and orders**, suggesting a seasonal peak.  

---

## **8. How to Use the Project**
1. Clone the repository to your local system.  
2. Open the `ExcelDashboard.xlsx` file.  
3. Navigate to the **Dashboard** sheet.  
4. Use slicers to filter and interact with the data dynamically.  

---

## **9. Skills Demonstrated**
- **Power Query**: Data cleaning and transformation.  
- **Pivot Tables**: Efficiently summarizing and analyzing data.  
- **Charts**: Advanced data visualization techniques.  
- **Excel Dashboards**: Creating responsive and interactive dashboards.  
