# Chicken Republic Stockout & Demand Analysis Dashboard 🍗📊

A comprehensive 5-page Power BI business intelligence project inspired by a real-world customer frustration: walking into a busy QSR (Quick Service Restaurant) branch during the evening rush only to find key menu items sold out. 

This project simulates retail and inventory metrics across major Lagos hubs (**Ajah, Lekki, Ikeja, Surulere, and Yaba**) to identify supply chain gaps, quantify lost revenue, and provide actionable inventory optimization strategies.

---

## 🚀 Project Overview & Problem Statement
In the Quick Service Restaurant industry, a **stockout** doesn't just mean a missed transaction; it impacts customer loyalty and long-term brand retention. This project analyzes operational logs to uncover:
* Which branches and product lines suffer from the highest stockout rates.
* The direct financial impact (Lost Revenue) of inventory gaps.
* How external factors (time of day, weather, promotional periods) drive demand patterns.

---

## 🛠️ Tech Stack & Skills Demonstrated
* **Business Intelligence:** Power BI Desktop
* **Data Modeling:** Star schema architecture with localized date, time, and branch dimensions.
* **DAX (Data Analysis Expressions):** Advanced calculated columns and measures for dynamic KPIs, moving averages, and variance analysis.
* **UI/UX Design:** Built a customized dashboard theme leveraging the **Chicken Republic** corporate color palette—utilizing high-contrast red (`#D21219`) and yellow (`#FDB813`) accents against a clean, scannable canvas layout to maximize stakeholder readability.

---

## 📉 Key Business Insights Uncovered

* **Financial Drain:** An overall stockout rate of **0.22** accounted for approximately **₦12M in Total Lost Revenue** across the tracked operational timeline.
* **The Evening Bottleneck:** Stockouts are non-linear and highly time-dependent. A massive spike occurs between **6:00 PM and 8:00 PM (Hours 18–20)**, aligning perfectly with the post-work dinner rush.
* **Branch Disparities:** While **Lekki** dominates total sales volume, **Ajah** experiences the highest operational risk with a branch stockout rate of **0.29**.
* **Stocking Inefficiencies:** The analysis reveals a **-6.28 stock adjustment variance**, indicating that standard static morning opening stock baselines (~120 units) fail to adapt to fluid, time-of-day demand patterns.

---

## 🖥️ Dashboard Architecture & Interface

The interactive report is broken down into 5 targeted analytical views:

### 1. Executive Stockouts Overview
*High-level summary of operational health, total lost revenue, and branch-by-branch stockout frequencies.*
![Executive Stockouts]([path/to/screenshot_page1.jpg](https://github.com/Ballistic-02/Chicken-Republic-Analysis/blob/main/Charts%20for%20chicken%20republic/Screenshot%20(1055).png))

### 2. Stockout Deep-Dive
*Granular tracking of days with stockouts correlated against specific operational hours and core product lines.*
![Stockout Overview](path/to/screenshot_page2.jpg)

### 3. Demand Patterns
*Time-intelligence analysis tracking hourly fluctuations, unit sales distribution, and peak day-of-week trends.*
![Demand Patterns](path/to/screenshot_page3.jpg)

### 4. External Drivers
*Evaluates the impact of weather conditions (Rainy vs. Sunny) and active marketing promotional periods on branch footfall and inventory depletion rates.*
![External Drivers](path/to/screenshot_page4.jpg)

### 5. Stocking Efficiency
*Operational metrics comparing leftover stock baselines against suggested opening inventory metrics to mitigate variances.*
![Stocking Efficiency](path/to/screenshot_page5.jpg)

---

## 💡 Recommendations for Stakeholders
1. **Dynamic Buffer Stocking:** Transition from static morning stocking to a bifurcated replenishment strategy, injecting a secondary inventory buffer right before the **Hour 18 (6:00 PM)** dinner rush.
2. **Targeted Supply Reallocation:** Prioritize supply chain distribution lines toward the **Ajah branch** to bring its 0.29 stockout rate back down to the regional baseline.
3. **Core Product Safeguards:** Implement strict minimum threshold tracking on high-velocity items (e.g., core Fried Chicken lines) to ensure steady revenue retention.

---

## 📂 How to Explore the Project
1. Clone this repository to your local machine.
2. Open the `.pbix` file using **Power BI Desktop**.
3. Ensure your local environment supports the dataset connections or interact with the published dashboard layout via screenshots provided above.
