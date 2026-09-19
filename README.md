# 🏠 Real Estate Insight – Tableau Dashboard

![Tableau](https://img.shields.io/badge/Tableau-Dashboard-blue?logo=tableau)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

## 📖 Project Overview

This Tableau dashboard analyzes real estate sales data to understand sales trends, town-wise performance, property types, sales ratios, and geographical distribution.

The project transforms raw real estate data into meaningful business insights using interactive dashboards, KPIs, filters, parameters, dynamic navigation, dashboard actions, geographical analysis, and Tableau storytelling.

---

# 🎯 Project Objectives

- Analyze real estate sales trends from 2011 to 2022.
- Measure overall sales amount, transactions, and assessed value.
- Compare real estate performance across different towns.
- Analyze sales ratios by town and residential property type.
- Explore geographical distribution of real estate sales.
- Understand property type composition.
- Build an interactive dashboard for data-driven analysis.
- Present key findings and recommendations through an Insights & Briefing view.

---

# 🛠️ Tools & Technologies

- Tableau Public
- Data Visualization
- Business Intelligence
- Interactive Dashboard Design
- Parameters
- Dynamic Zone Visibility
- Filters
- Highlight Actions
- Filter Actions
- URL Actions
- Geographical Maps
- Tableau Storytelling

---

# 📊 Dashboard Views

The project contains a single interactive Tableau dashboard with multiple views controlled through the dashboard navigation.

## 1️⃣ Home

![Geographical](Images/Geographical.png)

Provides an overall summary of the real estate dataset.

### KPIs

- 💰 Total Sales Amount: **$234,625,769,816.34**
- 🏠 Total Transactions: **526,276**
- 💵 Total Assessed Value: **$169,392,771,537.00**

### Visuals

- Assessed Value by Town
- Town-wise performance
- Interactive Metric Selector
- Town Filter
- State Filter

### Interactive Features

- Metric Selector
- Town Filter
- State Filter
- Dashboard Navigation

---

## 2️⃣ Timeline View

Analyzes year-over-year real estate sales trends.

### Visual

- 📈 Year-Over-Year Sales Trends

### Analysis Period

**2011 – 2022**

### Focus

- Annual sales performance
- Changes in total sales over time
- Identification of significant increases and decreases
- Overall real estate sales trend

The visualization shows a substantial increase in sales over the analysis period, with the highest visible sales level occurring in **2021**, followed by a decline in 2022.

---

## 3️⃣ Regional View

Analyzes sales ratio performance across towns and residential property types.

### Visual

- 📊 Average Sales Ratio by Town and Residential Type

### Residential Property Types

- Condo
- Four Family
- Single Family
- Three Family
- Two Family

### Analysis

This view allows users to compare average sales ratios across different towns and residential property types.

The heatmap format makes it easier to identify variations in sales ratio across locations and property categories.

---

## 4️⃣ Geographical View

Provides a geographical analysis of total real estate sales.

### Visual

- 🗺️ Total Sales Distribution Across States

### Features

- Geographical Map
- State-level visualization
- Town Filter
- State Filter
- Metric Selector
- Interactive Dashboard Navigation

The geographical view helps users explore how real estate sales are distributed across different states.

---

## 5️⃣ Insights & Briefing

Provides a summary of the major findings from the real estate analysis.

### Key Areas

- 📈 Market Trend
- 🏙️ Town Performance
- 🏠 Property Mix
- 💰 Business Insight
- 🎯 Recommendations
- 🔎 Overall Analysis

### Key Findings

- The dataset captures real-estate activity across **2011–2022**, showing changing transaction patterns and market performance over time.
- Sales are unevenly distributed across towns, with leading locations contributing a significant share of overall sales value.
- Sales Ratio provides an additional perspective by comparing market sales with assessed values.
- Residential properties dominate the dataset, with **Single Family** homes forming the largest residential segment.
- High sales value does not always indicate the strongest Sales Ratio, making both metrics useful for evaluating market performance.
- The analysis highlights geographical and property-type differences that can support targeted real-estate analysis.

---

# ✨ Interactive Features

✔ Interactive Navigation Menu

✔ Dashboard View Parameter

✔ Dynamic Zone Visibility

✔ Metric Selector

✔ Town Filter

✔ State Filter

✔ Highlight Action

✔ Filter Action

✔ Dynamic URL Action

✔ Geographical Map

✔ Interactive KPIs

✔ Sales Trend Analysis

✔ Sales Ratio Analysis

---

# 🧭 Dashboard Navigation

The dashboard uses a parameter-driven navigation system to switch between different analytical views within a single dashboard.

### Navigation Options

- 🏠 Home
- 🌎 Geographical View
- 📈 Timeline View
- 📍 Regional View
- 💡 Insights & Briefing

Dynamic Zone Visibility is used to display the selected view while keeping the navigation menu available.

---

# 🔗 Dynamic URL Action

A dynamic URL action is implemented using the **Town** field.

When a town is selected, users can navigate to a corresponding web page using the town name.

Example URL structure:

```text
https://en.wikipedia.org/wiki/<Town>
