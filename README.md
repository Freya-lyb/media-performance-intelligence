# Media Performance Intelligence: TV Attribution & Advertising Analytics
![Python](https://img.shields.io/badge/Python-Analytics-blue)

![Tableau](https://img.shields.io/badge/Tableau-Business%20Intelligence-orange)

![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-lightgrey)

![Attribution](https://img.shields.io/badge/Focus-TV%20Attribution-green)

![Analytics](https://img.shields.io/badge/Type-Media%20Analytics-purple)

![Dashboarding](https://img.shields.io/badge/Visualization-Executive%20Dashboards-red)

## Overview

A media performance intelligence case study exploring television advertising efficiency, attribution reliability, and network-level optimization through Python analytics and Tableau dashboards.

This project combines business intelligence, attribution analytics, KPI engineering, and executive-facing visualization to evaluate how television advertising performance varies across networks and over time. The analysis focuses on identifying which TV networks deliver scalable and cost-efficient customer acquisition while validating whether TV airings generate measurable short-term traffic impact.

Rather than relying solely on traditional survey attribution, the project integrates traffic-response analysis to evaluate whether TV exposure produces immediate website engagement beyond baseline traffic levels.

The final workflow combines:

- performance analytics
- attribution validation
- KPI engineering
- dashboard storytelling
- temporal trend analysis
- budget optimization strategy
- executive-facing business intelligence

---

# Business Problem

Television advertising represents a major acquisition channel, but advertising efficiency varies substantially across networks.

Traditional attribution methods based on customer surveys often fail to fully capture TV’s short-term impact on online engagement. As a result, media buyers face two major challenges:

- determining which networks generate efficient customer acquisition
- validating whether TV airings actually drive measurable traffic lift

This project explores:

- Which networks deliver scalable and efficient performance?
- How does TV performance evolve over time?
- Do TV airings generate measurable short-term traffic impact?
- How can attribution confidence be improved?
- Where should advertising budget be reallocated?

---

# Analytical Workflow

The project followed a hybrid analytics and attribution workflow designed to combine operational KPI analysis with behavioral traffic validation.

```text
Raw advertising & traffic data
→ Data cleaning & standardization
→ KPI engineering
→ Performance aggregation
→ Network-level analysis
→ Temporal trend analysis
→ Attribution traffic analysis
→ Dashboard development
→ Executive recommendations
```

The final analysis integrated:

- advertising spend data
- customer survey attribution
- TV airing schedules
- minute-level traffic behavior
- network-level performance metrics

---

# Dataset Scope

## Core Data Sources

### Purchase Exit Survey

Survey responses from customers who reported hearing about the product through television advertising.

### Daily Airings Data

Daily network-level spend and lift metrics used to evaluate overall TV performance efficiency.

### Spot-Level Airings Data

Timestamp-level TV airing records used for attribution and traffic-response analysis.

### Site Traffic Data

Minute-level website traffic and baseline traffic estimates used to evaluate short-term post-airing traffic lift.

---

# Data Cleaning & KPI Engineering

A major portion of the project focused on preparing fragmented advertising and attribution datasets into a unified analytical framework suitable for business intelligence reporting.

## Data Preparation Tasks

- Standardized inconsistent network naming
- Handled missing and “Other” network responses
- Removed incomplete or invalid observations
- Processed negative and zero-lift edge cases
- Unified timestamp and month formatting
- Prepared Tableau-ready aggregated datasets
- Created attribution-ready traffic alignment tables

## KPI Construction

The project engineered core advertising performance metrics including:

### CPM — Cost Per Mille

```text
Spend / Impressions × 1000
```

Measures media delivery cost efficiency.

### CPV — Cost Per Visitor

```text
Spend / Lift
```

Measures the cost required to generate incremental traffic.

### CR — Conversion Rate

```text
TV Attributable Purchases / Lift
```

Measures traffic conversion effectiveness.

### CPA — Cost Per Acquisition

```text
Spend / TV Attributable Purchases
```

Measures customer acquisition efficiency.

---

# Performance Analysis

## Overall TV Performance

The campaign demonstrated meaningful operating scale:

- Approximately $554K in total spend
- Approximately 8K attributable purchases
- Approximately $69 overall CPA

The analysis showed that TV advertising can drive measurable acquisition volume, but aggregated performance masks substantial network-level variation.

---

## Network-Level Efficiency Gaps

One of the strongest findings was the large performance disparity across networks.

Key findings included:

- Performance was concentrated within a small number of high-value networks
- Several high-spend networks delivered below-average efficiency
- Top-performing networks achieved acquisition costs less than half of underperforming networks
- Efficiency and scale did not consistently align

This suggested strong opportunities for strategic budget reallocation.

---

## Temporal Performance Trends

The analysis compared monthly performance patterns across the campaign period.

Key findings included:

- Spend increased from April to May
- Purchases increased alongside spend expansion
- CPA improved from April to May
- Conversion rates strengthened over time
- June data appeared operationally incomplete and unsuitable for optimization decisions

The results suggested that campaign efficiency improved as the campaign scaled.

---

# TV Attribution Analysis

A major component of the project focused on validating TV attribution using traffic-response analysis rather than relying exclusively on customer survey reporting.

## Attribution Methodology

TV airing timestamps were aligned with subsequent website traffic activity at the minute level.

The analysis estimated short-term incremental traffic lift immediately following TV airings in order to evaluate whether TV exposure produced measurable behavioral response.

## Key Findings

### Immediate Traffic Response

Website traffic consistently increased immediately following TV airings.

Key observations included:

- Traffic spikes peaked within the first minute after airing
- Visitor counts exceeded baseline traffic levels
- TV exposure showed measurable short-term engagement effects

This provided strong directional evidence supporting TV attribution validity.

---

## Network-Level Attribution Variation

Traffic-response analysis also revealed substantial variation across networks.

Key findings included:

- A small subset of networks generated disproportionate traffic lift
- Traffic response consistency varied significantly within networks
- Some networks generated high spend with weak behavioral response

This reinforced the importance of network selection in overall media ROI optimization.

---

# Recommendations

## Budget Allocation

- Reallocate spend toward networks delivering both low CPA and strong traffic lift
- Reduce or pause investment in consistently inefficient networks
- Prioritize scalable high-efficiency channels

## Network Strategy

- Favor networks demonstrating stable performance across multiple airings
- Evaluate consistency rather than relying only on average performance
- Expand investment in high-performing network segments

## Attribution Improvement

- Combine survey attribution with traffic-response validation
- Exclude incomplete periods from optimization decisions
- Improve confidence through multiple attribution signals

---

# Dashboard Development

Interactive Tableau dashboards were developed to support executive-facing business intelligence reporting.

## Dashboard Capabilities

- Overall campaign KPI tracking
- Monthly performance analysis
- Network-level efficiency comparison
- Attribution traffic visualization
- Scale vs efficiency analysis
- Temporal trend analysis

The dashboards were designed to support recurring campaign reporting and future optimization workflows.

---

# Technical Stack

## Languages & Libraries

- Python
- pandas
- NumPy
- matplotlib

## BI & Visualization

- Tableau
- Interactive dashboards
- Executive KPI reporting

## Analytical Focus Areas

- Media attribution
- KPI engineering
- Traffic-response analysis
- Performance analytics
- Budget optimization
- Business intelligence

---

# Repository Structure

```text
media-performance-intelligence/
│
├── analytics/        # Python analysis & KPI engineering
├── dashboards/       # Tableau packaged workbooks
├── visuals/          # Dashboard previews & analytical charts
├── reports/          # Executive reports & presentations
└── README.md
```

---

# Project Positioning

This repository is intentionally positioned as:

- a media attribution analytics case study
- a business intelligence & dashboarding project
- a TV advertising performance investigation
- a KPI engineering and optimization workflow
- an executive-facing analytics portfolio project

It is intentionally NOT positioned as:

- a generic Tableau assignment
- a dashboard-only visualization project
- a simple marketing analytics exercise
- a survey reporting workflow
- a classroom business intelligence project

---

# Key Themes

- media-performance-intelligence
- attribution-analytics
- business-intelligence
- advertising-analytics
- dashboard-storytelling
- KPI-engineering
- budget-optimization
- TV-attribution
- performance-analytics
- executive-reporting
- network-efficiency-analysis
- traffic-response-analysis
