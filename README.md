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

## **Key Business Insights**  
Some key insights generated from the dashboard include:  
1. **Peak Time Slots**: Analyze which time slots generate the most revenue and bookings.  
2. **Revenue Growth Trends**: Identify upward/downward monthly trends in bookings and revenue.  
3. **Booking Status Analysis**: Compare the contribution of confirmed vs pending bookings to total revenue.  
4. **Customer Segmentation**: Identify top customers based on total revenue and frequent bookings.  

---

## Tools and Technologies  
- **Power BI Desktop**: Data cleaning, modeling, and visualization  
- **Power Query**: Data transformation and table creation  
- **DAX (Data Analysis Expressions)**: Calculated measures and KPIs  
- **Excel**: Initial data source  

---

## **Data Model Overview**

Below is the Power BI Data Model used for this dashboard, showing key relationships between tables:

![Data Model](./Data Model.png)



