# **Power BI Service Bookings Dashboard**

## **Problem Statement**  
The company is facing challenges in optimizing and analyzing service bookings due to insufficient visibility into key metrics such as total revenue, booking trends, time slot performance, and customer behavior.  
The lack of an effective monitoring system results in:  
- Difficulties tracking confirmed and pending bookings.  
- Challenges understanding revenue distribution across different time periods.  
- Missed opportunities in identifying top-performing services, instructors, and customers.  

This has led to missed opportunities for operational efficiency, potential revenue growth, and improved customer satisfaction.  
To address these gaps, there is a need to develop a dynamic, data-driven dashboard that can provide actionable insights and support better decision-making.  

---

## **Project Overview**  
This project aims to create an interactive Power BI dashboard that provides critical insights into service bookings, revenue trends, time slot analysis, and booking status.  
The dashboard enables better operational planning, customer engagement, and revenue tracking by visualizing key performance metrics.  

---

## **Data Cleaning Process**  
Steps followed for data preparation:  
- **Imported Excel file into Power BI.**  
- **Checked column quality using Power Query.**  
- **Removed a column with completely null values.**  
- **Created and transformed multiple tables, including the Customer Table and Date Table, using Power Query.**  
- **Loaded cleaned tables into Power BI and built relationships to create a robust data model.**  
- **Defined key measures to track KPIs like Total Revenue, Total Bookings, MoM Growth, and Avg Booking Price.**  
- **Designed and developed an interactive dashboard to visualize key metrics and trends.**  

---

## **Key Measures Created**  
- **Avg Booking Price**  
- **Confirmed Revenue**  
- **Confirmed Revenue %**  
- **MoM Booking Change with Symbol**  
- **MoM Change Bookings**  
- **MoM Change Revenue**  
- **MoM Revenue Change with Symbol**  
- **Pending Revenue**  
- **Pending Revenue %**  
- **PM Bookings (Previous Month Bookings)**  
- **PM Revenue (Previous Month Revenue)**  
- **Total Bookings**  
- **Total Customers**  
- **Total Revenue**  

---

## **Dashboard Visuals**  
Below is a summary of the dashboard visuals with their respective names:  

1. **Total Customers Card** → **"Total Customers Overview"**  
   - Displays the total number of unique customers.  
2. **Avg Booking Price Card** → **"Average Booking Price"**  
   - Shows the average price per booking.  
3. **Confirmed Revenue Card** → **"Confirmed Revenue Analysis"**  
   - Provides the total revenue from confirmed bookings.  
4. **Pending Revenue Card** → **"Pending Revenue Overview"**  
   - Shows the total revenue for pending bookings.  
5. **Monthly Bookings/Revenue Growth (%) Line Chart** → **"Monthly Growth Analysis (Bookings & Revenue)"**  
   - Tracks the monthly growth rate of bookings and revenue.  
6. **Revenue Split by Booking Status / Booking Type / Service Name Stacked Bar Chart** → **"Revenue Distribution by Booking Status, Type, and Service"**  
   - Breaks down revenue based on booking status (Confirmed/Pending), booking type, and service.  
7. **Weekly Trend of Revenue and Bookings (Line and Column Chart)** → **"Weekly Trend: Total Bookings and Revenue"**  
   - Visualizes the week-by-week trend in bookings and revenue.  
8. **Month & Weekly Bookings/Revenue and Avg Price Matrix** → **"Monthly & Weekly Insights: Bookings, Revenue, and Average Price"**  
   - A matrix showing bookings, revenue, and average price across months and weeks.  
9. **Revenue and Bookings by Time Slot (Matrix)** → **"Time Slot Analysis: Total Revenue, Bookings, and Avg Price"**  
   - Displays revenue and bookings based on time slots (9 AM to 5 PM, one-hour intervals).  
10. **Pending vs Confirmed Revenue Pie Chart** → **"Booking Status Breakdown: Confirmed vs Pending"**  
    - Compares the revenue generated by confirmed vs pending bookings.  
11. **Clear All Filters Button** → **"Reset Filters"**  
    - A button to reset all slicers and filters on the dashboard to default values.  

---

# Here are the key business insights derived from the dashboard:

# Key Business Insights:

### **Booking Consistency:**  
   - The data shows that each customer makes **exactly one booking per month**.

### **Average Booking Price Trend:**  
   - The average booking price increased steadily from **₹137.51 in March** to **₹144.53 in June**, suggesting that **higher-value bookings may have offset the decline in total bookings**.

### **Pending Revenue Concerns:**  
   - Nearly **half the revenue remains pending across the months**, indicating persistent opportunities to enhance collections and customer engagement:  
     - **49.39% in March**  
     - **54.09% in April**  
     - **52.77% in May**  
     - **49.43% in June**  

### 1. Facility Services:
- Gradual improvement in reducing pending revenue.
  - Starting with a high of 72.19% in March.
  - Decreased to 55.13% in May.
  - Further improved to 53.11% in June.

### 2. Birthday Party:
- **Average booking price declines** in April and May.
  - Possible reason: Discounts or smaller party sizes.
- **Pending revenue increases**, indicating delays or incomplete payments during these months.

### 3. Instructor James Howard:
- **Pending revenue percentage shows a concerning rise**, increasing from **40.42% in March to 53.90% in June**, reflecting growing payment delays.
- The **average booking price has slightly decreased**, from **₹145.20 in March to ₹139.75 in June**, which may indicate:
  - A potential impact on revenue per booking.
  - A possible need to investigate reasons for the reduced pricing or lower-value bookings.

### 4. Instructor Lisa Hensley:
- **Pending revenue percentage improves significantly**, dropping from **53.04% in May to 29.76% in June**.
- Accompanied by an **increase in the average booking price from ₹121.21 to ₹144.16**.

### 5. Time Slot Analysis:
- **2 PM time slot generates the highest total revenue**, reflecting strong customer engagement and demand.
- **3 PM slot records the highest average booking price**, indicating premium bookings or higher service rates compared to other slots.

### 6. Party Room: Payment Challenges

- Pending revenue remains **persistently high**, peaking at **72.73% in March** and staying above **50%**  
(**51.35% in May**, **57.42% in June**), reflecting ongoing payment collection issues despite slight improvements.


# Recommendation: 

## Focus on Pending Payments

With consistently high pending revenue (averaging nearly 50% across months), prioritize improving payment collections by implementing:

- **Automated Payment Follow-Ups:**  
  Send reminders to customers with outstanding balances.  

- **Early Payment Incentives:**  
  Offer discounts or rewards for timely payments to encourage faster clearance.  

- **Flexible Payment Plans:**  
  Allow installment options to reduce financial burden and improve cash flow.  

- **Payment Visibility:**  
  Enhance transparency by providing customers with easy access to pending payment details.

## Optimize Slot Performance

- **Focus on Premium Slot (3 PM)**: Maximize revenue by leveraging the highest average booking price.  
- **Utilize High-Demand Slot (2 PM)**: Capitalize on strong demand by enhancing services or optimizing pricing.  
- **Address Low-Demand Slots (5 PM, 9 PM)**: Boost demand through targeted promotions, discounts, or special offers to improve slot utilization.  

---

## Tools and Technologies  
- **Power BI Desktop**: Data cleaning, modeling, and visualization  
- **Power Query**: Data transformation and table creation  
- **DAX (Data Analysis Expressions)**: Calculated measures and KPIs  
- **Excel**: Initial data source  

---

## **Data Model Overview**

Below is the Power BI Data Model used for this dashboard, showing key relationships between tables:

![Data Model](./Data%20Model.png)




