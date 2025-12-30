# 📊 Clickstream E-commerce Conversion Funnel Analysis (Power BI)

## 📌 Project Overview
This project analyzes **e-commerce clickstream data** to understand user behavior across the shopping journey and identify **where users drop off before completing a purchase**.

The dashboard is built using **Power BI** and helps product and marketing teams gain visibility into:
- Conversion funnel performance  
- Device-wise behavior (Mobile vs Desktop)  
- Traffic source quality  
- Cart abandonment patterns  

---

## 🎯 Business Problem
An e-commerce business faces:
- High website traffic  
- Low purchase conversion rate  

However, the business lacks insights into:
- Which funnel stage causes maximum drop-off  
- Whether mobile users face more issues than desktop users  
- Which traffic sources drive high-quality vs low-quality users  

---

## 💡 Solution
An interactive Power BI dashboard was developed to:
- Track the full user journey (Homepage → Purchase)
- Identify major drop-off points
- Compare conversion behavior by device and traffic source
- Analyze cart abandonment trends
- Support data-driven product and marketing decisions

---

## 🧱 Data Model
The project uses a **Star Schema** for optimal performance and clarity.

### Fact Tables
- WebEvents (Clickstream events)
- Sessions
- Orders

### Dimension Tables
- Date
- Users
- Devices
- Products
- Traffic Source

Relationships are designed to avoid ambiguity and ensure correct filter propagation.

---

## 📈 Key Metrics (DAX)
- Sessions  
- Total Orders  
- Conversion Rate (%)  
- Cart Abandonment Rate (%)  
- Average Order Value (AOV)  
- Funnel Step Session Counts  

---

## 📊 Dashboard Pages

### 1️⃣ Conversion Funnel
- Visualizes the user journey:
  - Homepage → Product Page → Add to Cart → Checkout → Purchase
- Identifies high drop-off stages
- Device slicers highlight mobile checkout issues

---

### 2️⃣ Traffic & Performance Analysis
- Total Revenue by Traffic Source
- Conversion Rate by Traffic Source
- Sessions by Traffic Source
- Helps distinguish high-volume vs high-quality channels

---

### 3️⃣ Cart Drop-Off Analysis (Optional)
- Focuses on sessions that added items to cart but did not purchase
- Analyzes abandonment by device and traffic source
- Supports UX and technical issue identification

---

## 🛠 Tools & Technologies
- Power BI Desktop
- DAX
- Microsoft Excel (data source)
- Data Modeling (Star Schema)

---

## 📌 Key Insights
- Mobile users show higher drop-off during checkout
- Some traffic sources drive high traffic but low conversion
- Returning users generally have higher conversion and AOV

---

## 🚀 Business Impact
This dashboard helps teams:
- Identify and fix conversion bottlenecks
- Improve mobile checkout experience
- Optimize marketing spend
- Increase overall conversion rate and revenue

---

## 🧠 Learnings
- Clickstream data modeling
- Funnel and drop-off analysis
- DAX evaluation context handling
- Designing dashboards for real business users

---

## 📂 How to Use
1. Download the Power BI file
2. Open it using Power BI Desktop
3. Use slicers (Date, Device, Traffic Source) to explore insights

---

## 👤 Author
**Niranjan Singh**  
Aspiring Data / BI Analyst  

---

⭐ If you find this project useful, feel free to star the repository!
