# excel-global-electronics-analysis
# Interactive Global Retail Performance Analytics

## 📑 Project Overview
This project delivers a comprehensive Business Intelligence solution for a multi-national retail dataset. Using **Excel’s Modern BI Stack (Power Query & Power Pivot)**, I transformed fragmented raw data into a fully automated, interactive dashboard to monitor key performance indicators (KPIs) and drive data-led decision-making.

---

## 📸 Dashboard Preview
<img width="1783" height="749" alt="Dashboard Screenshot" src="https://github.com/user-attachments/assets/2b7e0e6c-5d71-45b7-93ae-969892a2bfc4" />


> *The dashboard features dynamic filtering by Year and Store, providing a high-level view of Revenue, Order Volume, and Shipping Efficiency.*

---

## 🛠️ Technical Implementation (The "How")

### 1. Data Modeling (Star Schema)
Built a robust **Star Schema** by connecting a central Fact table (Sales) with six Dimension tables (Products, Stores, Customers, Calendar, etc.). 
- **Benefit:** Optimized report performance and ensured data integrity across 30,000+ records.

### 2. Advanced DAX Calculations
Developed 20+ custom measures to extract deep business insights, including:
- **Time Intelligence:** Calculated **YoY (Year-over-Year)** and **Revenue LY** growth to identify seasonal trends.
- **Context-Aware Metrics:** Optimized the `Average Delivery Time` calculation to specifically account for **Store 0 (Online Fulfillment Centre)**, ensuring shipping KPIs weren't skewed by brick-and-mortar logic.
- **Dynamic Currency Conversion:** Implemented `SUMX` and `RELATED` logic to automate revenue conversion from local currencies to USD.

### 3. Automated ETL Pipeline
Used **Power Query (M)** to clean and shape the data, including handling date formats, creating actionable keys for different dimensions, merging product subcategories, and removing duplicates, making the report "one-click" refreshable.

---

## 💡 Strategic Business Insights

By analyzing the data patterns, I have identified several key trends that directly impact operational strategy and inventory management:

* **Seasonality & Inventory Optimization:** Identified a consistent annual cyclicality where **April represents the revenue trough**, while **December serves as the annual peak**. This trend provides a data-driven baseline for **stock procurement and logistics labor planning** to ensure adequate fulfillment capacity during the Q4 peak period.

* **Pandemic Impact Analysis:** Observed a significant downturn in **March 2020** performance. Revenue levels showed a sluggish recovery compared to pre-pandemic benchmarks, suggesting a fundamental shift in market conditions or long-term consumer sentiment that requires strategic adaptation.

* **Logistics Efficiency & Product Mix:** Detected a counter-intuitive **improvement in delivery lead times** during the 2020 peak. Analysis suggests this was driven by a **Product Mix shift**: a transition from bulky "Home Appliances" to smaller, high-velocity "Computers & Electronics," which streamlined warehouse handling and last-mile delivery.

* **AOV (Average Order Value) Contraction:** Analyzed a **20% decline in AOV** from $2,457 (2016) to $1,948 (2019). This trend indicates a strategic shift in volume toward the **Computer category**, characterized by higher purchase frequency but lower individual unit prices compared to earlier premium appliance sales.

* **Consumer Behavior Shifts during COVID-19:** Identified a clear **re-prioritization of household spending** during the pandemic. Demand for **TVs and Cell Phones** surged as customers optimized for remote entertainment and connectivity, while discretionary categories like "Cameras" and "Home Appliances" saw a contraction in relative market share.

---

## 📂 Project Structure
- `Retail_Analysis_Dashboard.xlsx`: The primary BI tool containing the Data Model and Visualizations.
- `Data/`: Source CSV files used for the ETL process.

---

## 👤 Contact & Connectivity
I am a budding Data Analyst passionate about turning messy data into actionable stories. 
- **LinkedIn:** [Your Profile Link]
- **Email:** [Your Email Address]
