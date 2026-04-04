# 🛒 E-commerce Analysis

## 🎯 Objective
To analyze customer purchasing behavior and identify key revenue drivers using RFM segmentation and decile analysis.

---

## 🧠 Analysis Process

### 1. 🧹 Data Preparation and Cleaning

**Extract Relevant Data:**
- Transaction-level data
- Customer profiles
- Time-based activity details

**Key Fields:**
- Customer ID
- Transaction Date
- Purchase Amount
- Product Categories

**Data Cleaning Steps:**
- Handle missing values
- Remove inconsistencies (invalid dates, negative amounts)
- Treat outliers

---

### 2. 📊 Exploratory Data Analysis (EDA)

**Understand the Dataset:**
- Distribution of total sales
- Average purchase size
- Frequency of transactions
- Number of active customers

**Trend Analysis:**
- Revenue trends (weekly, monthly, yearly)
- Seasonal patterns
- Category-wise purchasing behavior

---

### 3. 👥 RFM Segmentation

**Objective:**  
Segment customers based on:

- **Recency (R):** Days since last purchase  
- **Frequency (F):** Number of transactions  
- **Monetary (M):** Total spending  

**Steps:**
- Calculate R, F, M for each customer
- Assign scores (1–5 scale)
- Combine scores (e.g., 555 = high value)
- Segment customers into:
  - Loyal Customers
  - At-Risk Customers
  - Dormant Customers

---

### 4. 🔢 Decile Analysis

**Objective:**  
Rank customers into 10 groups based on performance.

**Steps:**
- Sort customers by revenue or frequency
- Divide into 10 equal segments

**Insights:**
- **Top 10% (Decile 1):** Highest revenue contributors  
- **Bottom 10% (Decile 10):** Low engagement customers  

---

### 5. 💡 Business Recommendations

Based on RFM and decile analysis:

- **Retention:**  
  Target high-value customers with loyalty programs

- **Re-engagement:**  
  Run campaigns for inactive customers

- **Upselling:**  
  Focus on mid-tier customers to increase spending

---

### 6. 📈 Visualization & Dashboard

Dashboard created using Power BI showcasing:

- RFM segmentation heatmaps  
- Decile-wise revenue contribution  
- Customer behavior trends over time  

**Key Insight:**
> Targeting top deciles (1–3) can maximize ROI through personalized marketing strategies.

---

## 🛠 Tools Used
- Excel
- SQL (optional)
- Power BI

---

## 📌 Key Takeaways
- A small percentage of customers contribute majority of revenue
- Customer segmentation helps in targeted marketing
- Data-driven strategies improve retention and revenue growth
