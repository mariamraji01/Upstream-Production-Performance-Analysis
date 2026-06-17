# 🛢️ Upstream Oil & Gas Production Performance Analysis

### End-to-End Data-Driven Analysis of Nigerian Deepwater Assets

![Project Cover](https://github.com/mariamraji01/Upstream-Production-Performance-Analysis/blob/main/Cover%20Image.jpeg)

---

## 📌 Project Overview

The upstream oil and gas industry relies heavily on efficient production operations, asset reliability, and effective downtime management to maximize output and sustain profitability.

This project presents an end-to-end Power BI analysis of Nigerian Deepwater Assets, designed to monitor production performance, evaluate operational efficiency, and identify wells that may require closer operational attention.

Through interactive dashboards, the analysis transforms raw production data into actionable insights that support data-driven decision-making across production, operations, and asset management teams.

---

## 🎯 Business Problem

Upstream oil and gas operators continuously balance production targets, operational efficiency, and asset reliability. However, production declines are often preceded by subtle warning signs such as increasing downtime, rising lifting costs, aging wells, and deteriorating equipment performance.

Without a centralized view of these indicators, operational issues may go unnoticed until they begin impacting production output and profitability.

This project was developed to provide a data-driven framework for monitoring production performance, identifying operational bottlenecks, and highlighting wells that may require proactive intervention.

---

## ❓ Key Business Questions

This analysis was designed to answer the following questions:

- Which fields and wells contribute the most to overall production?
- How has production performance changed over time?
- Do older wells experience higher downtime and lower efficiency?
- Which operational assets show signs of increased risk?
- How does downtime impact production performance?
- Which wells require closer monitoring due to declining reliability?
- What operational factors are driving production losses?

---

## 📊 Dataset Overview

The dataset contains operational and production-related information from Nigerian Deepwater Assets, including:

- Oil Production Volume
- Gas Production Volume
- Water Cut (%)
- Downtime Hours
- Well Life Classification
- Field Information
- Formation Information
- Flow Control Metrics
- Oil Quality Information
- Basin Information
- Operator Information
- Production Dates

---

## 🧹 Data Preparation & Transformation

Several data preparation and transformation steps were performed to improve analytical quality and reporting flexibility.

### Data Cleaning
- Removed inconsistencies and duplicates
- Standardized naming conventions
- Validated production and downtime records

### Feature Engineering
Created analytical categories including:

#### Well Life Classification
- New Wells
- Mid-Life Wells
- Mature Wells

#### Downtime Severity Bands
- Minor Issues
- Moderate Issues
- Serious Issues

#### Well Health Status
- Healthy
- Monitor
- At Risk

### Data Modeling

The dataset was transformed into a Star Schema model to improve report performance and analytical flexibility.

#### Model Components
- Fact Production Table
- Date Dimension
- Well Dimension
- Field Dimension
- Operator Dimension
- Basin Dimension
- Oil Quality Dimension
- Flow Control Dimension

This structure enabled efficient filtering, aggregation, and advanced DAX calculations.

---

## 📏 Key Metrics

The following KPIs were developed using DAX:

- Total Oil Production
- Total Gas Production
- Average Water Cut
- Average Daily Production
- Active Wells
- Total Downtime Hours
- Uptime Percentage
- Average Downtime Hours
- Year-over-Year Production Growth
- Well Health Status

---

# 📈 Dashboard Structure

---

## 1️⃣ Executive Overview

### Purpose

Provide a high-level view of production performance across wells, fields, and operational assets.

### Key Focus Areas

- Total Oil Production
- Total Gas Production
- Production Growth
- Average Water Cut
- Average Daily Production
- Active Wells
- Monthly Production Trend
- Top Producing Wells
- Production Distribution by Field

### Dashboard Preview

![Executive Overview](screenshots/executive-overview.png)

---

## 2️⃣ Operational Efficiency

### Purpose

Evaluate operational performance by examining uptime, downtime, and the impact of asset age on production efficiency.

### Key Focus Areas

- Uptime Performance
- Total Downtime Hours
- Average Downtime Hours
- Downtime Severity Distribution
- Well Life Distribution
- Downtime vs Well Age Analysis
- Production Efficiency Trends

### Dashboard Preview

![Operational Efficiency](screenshots/operational-efficiency.png)

---

## 3️⃣ Risk & Reliability

### Purpose

Identify wells showing signs of declining performance and operational risk.

### Key Focus Areas

- Well Health Status
- Reliability Monitoring
- Water Cut Impact
- Risk Classification
- Downtime Risk Assessment
- Well Performance Monitoring

### Dashboard Preview

![Risk & Reliability](screenshots/risk-reliability.png)

---

## 💡 Key Insights

### Production Performance

- Total oil production reached **8.2 million barrels** across the reporting period.
- Production recorded a strong **+33.6% year-over-year increase**, indicating improved asset performance.
- A small number of fields contributed a significant proportion of total production.

### Operational Efficiency

- Average uptime remained above **95%**, reflecting generally stable operations.
- Mature wells recorded higher downtime compared to newer wells.
- Increased downtime negatively impacted production efficiency.

### Risk & Reliability

- Wells with elevated downtime showed signs of declining operational performance.
- Higher water cut levels were associated with increased operational concerns.
- Several wells were identified for closer monitoring based on health status indicators.

---

## 🛠️ Technologies Used

- Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Data Modeling
- Star Schema Design
- Microsoft Excel

---

## 📈 Business Value

This dashboard provides stakeholders with a centralized view of production performance, operational efficiency, and asset reliability.

Key business benefits include:

- Improved production monitoring
- Early identification of operational issues
- Enhanced downtime visibility
- Better asset performance tracking
- Data-driven operational decision-making

---

## 🚀 Conclusion

Production optimization extends beyond increasing output. Sustainable operational success requires visibility into asset performance, downtime behavior, and reliability indicators.

This project demonstrates how production data can be transformed into actionable insights that support proactive operational management and improved decision-making within upstream oil and gas operations.

---

## 👩‍💻 Author

**Raji Mariam**

Data Analyst | Power BI | SQL | Data Storytelling

### Connect With Me

- LinkedIn: www.linkedin.com/in/mariam-raji055
- Email: mariamraji50@gmail.com

---

⭐ If you found this project interesting, feel free to connect with me and explore my other analytics projects.
