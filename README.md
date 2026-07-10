<div align="center">

# 📡 Telecom Executive Dashboard
### Multi-Page Power BI Solution — Revenue, Customer &amp; Network Performance

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Advanced-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

</div>

---

## 📌 Overview

A 6-page Power BI executive dashboard built for a telecom operator, covering revenue &amp; profitability, customer churn, network performance, marketing ROI, and customer experience. Designed to give leadership a single, drillable view across the full customer and network lifecycle.

## 🎯 Business Problem

Telecom executives need a consolidated view spanning revenue and margin trends, churn risk by region/segment, network reliability (uptime, dropped calls), customer acquisition cost efficiency, and customer satisfaction (NPS, FCR) — typically scattered across separate operational systems.

## 🛠️ Tools &amp; Technologies

<table>
<tr><td><b>BI Tool</b></td><td>Power BI Desktop &amp; Service</td></tr>
<tr><td><b>Data Modeling</b></td><td>DAX measures (Gross Margin %, ARPU, Churn Rate %, CAC, NPS, FCR Rate %)</td></tr>
<tr><td><b>Data Prep</b></td><td>Power Query (M Language)</td></tr>
<tr><td><b>Visuals</b></td><td>Decomposition tree, gauge charts, filled maps, ranked tables, KPI cards</td></tr>
</table>

## ✨ Key Features (6 Dashboard Pages)

**1. Overview**
- KPI cards: Total Revenue, Gross Profit, Gross Margin %, ARPU, Churn Rate %, New Customers.
- Customer segment split (B2B/B2C), revenue by region (map), revenue by plan type, and monthly revenue trend.
- Filters: Year, Quarter, Region, Segment.

**2. Revenue &amp; Profitability**
- Revenue ranked by plan name.
- Decomposition tree for strategic revenue deep-dive (Region → Plan Type → Segment).
- ARPU and Gross Margin % by segment, plus revenue &amp; gross profit trend by month.

**3. Customer &amp; Churn**
- Customer risk table (risk score, average downtime minutes per customer).
- Churned customers by region and city.
- Revenue and churn share by segment (B2B/B2C).
- Monthly churn rate % trend.

**4. Network Performance**
- Total calls vs. dropped calls by month.
- Average downtime minutes by city (map).
- Network uptime % vs. target uptime (gauge).
- Dropped call rate % trend by month.

**5. Acquisition &amp; Marketing ROI**
- Customer Acquisition Cost (CAC) vs. goal, with variance %.
- New customers by acquisition channel (App, Call Center, Corporate, Dealer, Kiosk, Online, Partner, Retail, Telesales, Website).
- Marketing spend vs. new customers trend by month.

**6. Customer Experience**
- Average NPS (gauge).
- First Call Resolution (FCR) rate % vs. goal.
- NPS by interaction type (Call, Chat, Store Visit).
- Monthly NPS trend.

## 📈 Dashboard Preview

<div align="center">

![Overview](screenshots/Screenshot%20telecom-01-overview.png)
![Revenue & Profitability](screenshots/Screenshot%20telecom-02-revenue.png)
![Customer & Churn](screenshots/Screenshot%20telecom-03-churn.png)
![Network Performance](screenshots/Screenshot%20telecom-04-network.png)
![Acquisition & Marketing ROI](screenshots/Screenshot%20telecom-05-acquisition.png)
![Customer Experience](screenshots/Screenshot%20telecom-06-experience.png)
<i>6-page dashboard: Overview · Revenue &amp; Profitability · Customer &amp; Churn · Network Performance · Acquisition &amp; Marketing ROI · Customer Experience</i>

</div>

## 📑 Full Presentation

📎 [View the full project presentation](WE_Telecom_Dashboard_Presentation.pptx)


## 🔍 Approach

1. **Data Preparation** — Cleaned and modeled billing, network, marketing, and customer service datasets using Power Query.
2. **Data Modeling** — Built DAX measures for ARPU, churn rate %, gross margin %, CAC, NPS, and FCR rate, with relationships across revenue, customer, network, and marketing tables.
3. **Dashboard Design** — Structured 6 focused pages so each function (Finance, Customer Ops, Network Ops, Marketing, CX) has a dedicated, drillable view.
4. **Advanced Visuals** — Used a decomposition tree for root-cause revenue analysis and gauge visuals for target-tracking (uptime, NPS, FCR).
5. **Interactivity** — Added year, quarter, region, city, and channel filters across pages.

## 📊 Key Insights

<!-- [ADD: any takeaway, e.g. "Churn rate spikes align with network dropped-call rate spikes in the same months, suggesting network reliability as a churn driver."] -->

## 🔒 Note on Data

This project uses a sample/practice dataset built to mirror real telecom analytics scenarios. Company and brand names shown are used for illustrative/learning purposes only and do not represent real company data or an official affiliation.

---

<div align="center">

**Sameh El-Hosary** | Data Analyst &amp; Business Intelligence Analyst
[LinkedIn](https://linkedin.com/in/sameh-el-hosary-) · [GitHub](https://github.com/SamehElhosary0) · [Email](mailto:sameh.sabry656@gmail.com)

</div>
