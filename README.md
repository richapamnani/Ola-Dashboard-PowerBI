# 📊 Ola Cab Company Performance Dashboard

## Project Overview

This Power BI project provides a comprehensive analytical dashboard designed to monitor and evaluate the operational performance of Ola, a leading ride-hailing company. The dashboard offers key insights across various facets of the business, including overall booking trends, vehicle-type specific performance, revenue generation, cancellation rates, and customer/driver ratings.

The objective of this dashboard is to empower stakeholders with actionable insights to optimize operations, enhance customer satisfaction, and drive business growth by identifying trends, areas of improvement, and successful strategies.

## ✨ Features & Dashboard Sections

The dashboard is structured into five main sections, accessible via a user-friendly navigation pane:

### 1. Overall Performance 
<img width="960" height="534" alt="" src="https://github.com/user-attachments/assets/a88f81d1-07be-498d-88dd-45647f2dbc40" />

   - **Booking Status Breakdown:** A pie chart illustrating the distribution of `Success`, `Canceled by Driver`, `Canceled by Customer`, and `Driver Not Found` bookings.
   - **Total Booking Value & Total Bookings:** Key performance indicators (KPIs) showing the cumulative value and count of all bookings.
   - **Booking Value by Booking Status (Area Chart):** Visualizes the financial impact of different booking outcomes over time or across categories.

### 2. Vehicle Type Performance 
<img width="956" height="538" alt="" src="https://github.com/user-attachments/assets/dfa2b1d3-9d7d-4a34-8e2d-5f233f0ace97" />

   - **Detailed Table View:** A matrix or table showcasing performance metrics for each vehicle type (`Prime Sedan`, `Prime SUV`, `Prime Plus`, `Mini`, `Auto`, `Bike`, `E-Bike`).
   - **Metrics include:** `Total Booking Value`, `Success Booking Value`, `Avg. Distance Travelled`, and `Total Distance Travelled` for each vehicle type. This allows for comparative analysis of fleet efficiency and popularity.

### 3. Revenue Analysis 
<img width="953" height="541" alt="" src="https://github.com/user-attachments/assets/3094d16a-3449-4ff2-ba25-18f7944ff99f" />

   - **Revenue by Payment Method (Bar Chart):** Breaks down total revenue based on payment channels (`Cash`, `UPI`, `Credit Card`, `Debit Card`, `Null`).
   - **Revenue by Ride Distance (Bar Chart):** Illustrates revenue trends daily or over time, segmented by ride distance, providing insights into revenue generation patterns.
   - **Date Slicer:** Allows dynamic filtering of revenue data for specific periods.

### 4. Cancellation Insights 
<img width="953" height="535" alt="" src="https://github.com/user-attachments/assets/d3c23eb7-059e-454a-b0a3-77ce86b9639d" />

   - **Total, Success, and Cancelled Bookings (KPIs):** High-level overview of booking outcomes.
   - **Canceled Rides by Customers (Pie Chart):** Categorizes customer-initiated cancellations by reason (`AC is Not working`, `Change of plans`, `Driver asked to cancel`, `Driver is not moving to...`, `Wrong Address`, `Null`).
   - **Canceled Rides by Drivers (Pie Chart):** Categorizes driver-initiated cancellations by reason (`Personal & Car related issue`, `Customer related issue`, `Customer was coughing...`, `More than permitted p...`).
   - **Date Slicer:** Enables filtering of cancellation data by date range.

### 5. Ratings Analysis 
<img width="948" height="537" alt="" src="https://github.com/user-attachments/assets/45525c8a-e7c5-46cf-8832-fd571e8259ee" />

   - **Rating of Customer and Driver (Line Chart):** A line chart displaying the `Sum of Customer_Rating` and `Sum of Driver_Ratings` over `Customer_ID`. This visualization helps to identify individual customer-driver rating trends and potential discrepancies or correlations.
   - **Note:** For a more granular view, a scatter plot with individual `Booking_ID` in the `Details` field would show a direct correlation between customer and driver ratings per ride. (The current view suggests a line chart aggregated by Customer ID.)

## 🛠️ Technologies Used

* **Power BI Desktop:** For data modeling, transformation, visualization, and dashboard creation.
* **DAX (Data Analysis Expressions):** For creating custom measures and calculated columns to enrich data insights.
* **Excel/CSV:** As potential data sources for raw operational data.

## 📈 Impact & Business Value

This dashboard provides:
* **Operational Visibility:** Real-time insights into booking performance, cancellations, and revenue streams.
* **Performance Benchmarking:** Comparison of different vehicle types and identification of top/underperforming segments.
* **Customer & Driver Experience Insights:** Understanding reasons for cancellations and correlation between ratings to improve service quality.
* **Data-Driven Decision Making:** Supports strategic planning for fleet management, marketing campaigns, and service improvements.

