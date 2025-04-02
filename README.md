# Supermarket Sales Analysis Dashboard

## 1. ASK: Understanding Business Needs
### Key Business Questions:
- How are sales performing across different branches over three months?
- Which product lines generate the most revenue and customer satisfaction?
- What are the peak shopping hours and preferred payment methods?

### Business Goals:
- Identify branch-wise sales trends for growth strategies.
- Evaluate top-performing product lines for better inventory management.
- Analyze customer shopping behaviors to enhance experience and efficiency.

---
## 2. PREPARE: Understanding the Data
### Dataset Overview:
- **Data Period:** January – March
- **Key Fields:**
  - `Invoice ID` – Unique transaction identifier.
  - `Date` – When the sale occurred.
  - `Day of the Week` – Helps analyze daily trends.
  - `Month` – Monthly sales performance.
  - `Branch` – Store location details.
  - `City` – Regional analysis.
  - `Product Line` – Category of the sold item.
  - `COGS` (Cost of Goods Sold) – Represents total sales.
  - `Payment Type` – Cash, Credit Card, or E-wallet.
  - `Rating` – Customer feedback score.
  - `Time & Hour` – Transaction timestamp for peak hour analysis.
  - `Customer Type` – Member vs. Non-member.
    ### Data Source:
The dataset used for this analysis is publicly available on [Kaggle](https://www.kaggle.com/datasets/lovishbansal123/sales-of-a-supermarket).


---
## 3. PROCESS: Data Cleaning & Preparation
- Removed missing values and inconsistencies.
- Extracted **Month** and **Day of the Week** from the `Date` field.
- Extracted **Hour** from the `Time` field.
- Created a **Time of Day** segment based on shopping hours (10 AM – 9 PM):
  - Morning (10 AM - 12 PM)
  - Afternoon (12 PM - 3 PM)
  - Evening (3 PM - 6 PM)
  - Night (6 PM - 9 PM)

**Tool Used:** Excel (Power Query)

---
## 4. ANALYZE: Key Performance Insights
### Sales Trends & Customer Behavior Analysis
1. **Branch Sales Performance:**
   - The highest revenue branch **C** contributed **34.24%** of total sales.
   - Branch **A** and **B** accounted for **32.88%** each.

2. **Product Line Performance:**
   - **Food and Beverages** was the best-selling category (17.38% of revenue).
   - **Food and Beverages** had the highest customer satisfaction (7.11 rating).
   - **Home and Lifestyle** had the lowest customer rating.
   - **Health and Beauty** had the lowest sales.

3. **Peak Shopping Hours & Customer Traffic:**
   - Sales peaked at **7 PM**, indicating strong evening shopping trends.

4. **Payment Method Preferences:**
   - **E-wallets** were the most used (34.50%).
   - **Cash** followed closely (34.40%).
   - **Credit Card** was the least used (31.10%).

5. **Monthly Sales Trends:**
   - Revenue grew by **(+12.6%) in March** compared to February.
   - **January had the highest sales.**

6. **Customer Satisfaction & Shopping Habits:**
   - **Overall average rating:** 7.03.
   - Highest-rated category: **Fashion Accessories.**

**Tool Used:** Excel (Power Query)

---
## 5. SHARE: Dashboard & Visualizations
### Excel Dashboard Overview
#### Top 4 KPIs in the First Row:
- **Total Revenue:** $307,587
- **Revenue Growth (March):** +12.6%
- **Peak Shopping Hour:** 7 PM
- **Top Payment Method:** E-wallet (34.5%)

### Visualizations Included:
- **Line Chart** – Sales trends across branches and peak hours.
- **Bar Chart** – Revenue by product category, customer satisfaction, and sales trends.

**Tool Used:** Excel (Pivot Table)

---
## 6. ACT: Recommendations for Business Growth
### Suggested Actions:
- **Optimize Staffing for Peak Hours:**
  - Since **7 PM is the busiest time**, ensure enough staff and streamline checkout processes.
- **Stock More of Best-Selling Products:**
  - Maintain high inventory for **top-selling product lines** to meet demand.
- **Encourage Digital Payments:**
  - Offer **discounts or cashback for E-wallet users** (34.5%) to promote faster checkouts.
- **Improve Customer Satisfaction:**
  - Address concerns in **low-rated product categories** to boost customer experience.

