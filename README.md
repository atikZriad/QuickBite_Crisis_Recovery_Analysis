# 🍽️ QuickBite Crisis Recovery Analysis

![Dashboard Preview](Dashboard_Screenshots/Home_Dashboard.png)

**Domain:** Food Delivery & Consumer Analytics  
**Function:** Crisis Recovery & Business Strategy  
**Tool:** Microsoft Power BI

---

## 🚨 Project Context

QuickBite Express is presented in this project as a Bengaluru-based food-delivery startup that experienced a business disruption in June 2025.

The analysis compares two periods:

- **Pre-crisis:** January–May 2025
- **Crisis period:** June–September 2025

The dashboard examines order volume, city and restaurant performance, cancellations, delivery service levels, revenue, and customer loyalty. It describes observed patterns in the data; it does not independently establish the causes of those changes.

## 📊 Executive Dashboard

![Home Dashboard](Dashboard_Screenshots/Home_Dashboard.png)

The executive page summarizes the main metrics and links to detailed analysis pages.

**Period analyzed:** January–September 2025

## 🧠 Analysis Overview

| # | Analysis | Focus |
|---|---|---|
| 1 | Monthly Orders Trend | Compare order volume before and during the crisis period |
| 2 | City Order Decline | Compare order declines across cities |
| 3 | Restaurant Order Decline | Identify restaurants with the largest percentage declines among those meeting the dashboard's order threshold |
| 4 | Cancellation Analysis | Compare cancellation rates across months and cities |
| 5 | Delivery SLA | Review actual delivery times and SLA compliance |
| 6 | Revenue Impact | Compare revenue across the two periods |
| 7 | Loyalty Impact | Review high-frequency customers with no orders during the crisis period |

---

## 1️⃣ Monthly Orders Trend

![Monthly Orders](Dashboard_Screenshots/Monthly_Orders.png)

**What the dashboard shows:**

- Monthly order volume falls sharply in June 2025 compared with preceding months.
- Monthly orders remain substantially below January–May levels through September.

**Business relevance:** This comparison provides a baseline for monitoring order-volume changes in subsequent periods.

## 2️⃣ City Order Decline

![City Decline](Dashboard_Screenshots/City_Decline.png)

**What the dashboard shows:**

- The displayed major cities have order declines of approximately **68–70%** between the pre-crisis and crisis periods.
- The exact percentage varies by city.

**Business relevance:** City-level comparisons help identify where order volume changed most and where further investigation may be useful.

## 3️⃣ Restaurant Order Decline

![Restaurant Decline](Dashboard_Screenshots/Restaurant_Decline.png)

**What the dashboard shows:**

- The displayed top 10 restaurants have order declines ranging from approximately **83% to 94%**.
- The visual applies a minimum pre-crisis order threshold, as indicated by the dashboard filter.

**Business relevance:** These results identify restaurants with substantial declines in the selected periods.

## 4️⃣ Cancellation Analysis

![Cancellation Analysis](Dashboard_Screenshots/Cancellation_Analysis.png)

**What the dashboard shows:**

- The cancellation rate rises from **6.06%** in the pre-crisis period to **11.93%** in the crisis period.
- This is an increase of **5.87 percentage points**.
- The city comparison shows differences in cancellation-rate changes across locations.

**Business relevance:** These changes indicate an area for further operational investigation.

## 5️⃣ Delivery SLA Performance

![Delivery SLA](Dashboard_Screenshots/Delivery_SLA.png)

**What the dashboard shows:**

- Average actual delivery time increases from approximately **39 minutes** before the crisis to **60 minutes** during the crisis period.
- SLA compliance decreases by **31.4 percentage points**.

**Business relevance:** These metrics highlight changes in delivery performance and provide a basis for monitoring service levels.

## 6️⃣ Revenue Impact

![Revenue Impact](Dashboard_Screenshots/Revenue_Impact.png)

**What the dashboard shows:**

- **Pre-crisis revenue:** approximately ₹37.62 million
- **Crisis-period revenue:** approximately ₹10.94 million
- **Difference between periods:** approximately ₹26.68 million
- **Revenue decline:** approximately **70.9%**

**Business relevance:** The comparison quantifies the revenue difference between the selected periods.

## 7️⃣ Loyalty Impact

![Loyalty Impact](Dashboard_Screenshots/Loyalty_Impact.png)

The dashboard defines high-frequency customers as customers with at least five orders during the pre-crisis period who recorded no orders during June–September 2025.

**What the current visual shows:**

- **49** churned high-frequency customers.
- **26** of these customers had a pre-crisis average rating above 4.5.

These counts reflect the current dashboard measures and definitions.

**Business relevance:** The displayed segment can be a starting point for further customer-retention analysis.

## 💼 Business Impact Summary

| Metric | Pre-crisis | Crisis period | Comparison |
|---|---:|---:|---:|
| Orders | 113.8K | 35.4K | Approximately 68.9% lower |
| Revenue | ₹37.62M | ₹10.94M | Approximately 70.9% lower |
| SLA compliance | 44.8% | 13.4% | Down 31.4 percentage points |
| Cancellation rate | 6.06% | 11.93% | Up 5.87 percentage points |
| Churned high-frequency customers | — | 49 | As defined by the loyalty measure |
| Churned high-frequency customers with pre-crisis average rating above 4.5 | — | 26 | Subset of the 49 displayed customers |

*Pre-crisis covers January–May 2025; the crisis period covers June–September 2025. Values are based on dashboard visuals and may be rounded.*

## 🧩 Tools & Techniques

- **Power BI:** Data modeling, relationships, Power Query, and dashboard development
- **DAX:** Period comparisons, order and cancellation metrics, revenue analysis, delivery SLA measures, and customer-level calculations
- **Visualization:** KPI cards, monthly trends, city and restaurant comparisons, and drill-down analysis
- **Data preparation:** Cleaning and shaping source data for analysis

## 🧠 Key Takeaways

- Order volume and revenue were substantially lower during June–September 2025 than during January–May 2025.
- The dashboard shows higher cancellation rates, longer average delivery times, and lower SLA compliance during the crisis period.
- City and restaurant comparisons reveal differences in the scale of order declines.
- The loyalty visual identifies a defined group of high-frequency customers with no recorded orders during the crisis period.

These are observed patterns in the analyzed data. Additional investigation would be required to determine causes and evaluate the effectiveness of potential recovery actions.

## 👤 Author

**Atik Riad**  
📧 [azrofficial20@gmail.com](mailto:azrofficial20@gmail.com)  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/atikzamanriad/)

---

## 💬 Summary

This Power BI project compares QuickBite's order, revenue, cancellation, delivery, city, restaurant, and customer metrics across pre-crisis and crisis periods in 2025. It demonstrates data preparation, modeling, DAX-based analysis, and dashboard storytelling to summarize business performance and identify areas for further investigation.