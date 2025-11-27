# 📊 Meta Ad Performance Analysis – Power BI Dashboard

A comprehensive analytics project designed to analyze advertising performance across Facebook and Instagram.
This dashboard evaluates campaign reach, engagement, conversions, demographics, geographics, and budget utilization to help businesses optimize their ad spend and maximize ROI.

## 📌 1. Project Overview
  - This project presents a complete analytics solution for Meta Ad Campaign Performance, enabling marketers to:
  - Compare Facebook vs Instagram performance
  - Track ad effectiveness across the entire funnel
  - Understand audience behavior (gender, age, geography)
  - Analyze budget utilization and ROI
  - Identify best-performing ad formats and time slots
## 📂 2. Dataset Description
| Table         | Description                                                         |
| ------------- | ------------------------------------------------------------------- |
| **ad_events** | Fact table storing impressions, clicks, comments, shares, purchases |
| **ads**       | Ad-level metadata (platform, ad type, targeting info)               |
| **campaigns** | Campaign-level strategy, budget, and duration                       |
| **users**     | Demographic + interest details of engaged users                     |

## 🎯 3. Problem Statement
Problem Statement 1: KPI Requirements
| KPI Category             | Metrics Included                                 |
| ------------------------ | ------------------------------------------------ |
| **Sales/Reach Overview** | Impressions, Clicks, Shares, Comments, Purchases |
| **Engagement Metrics**   | Engagements, CTR, Engagement Rate                |
| **Conversion Metrics**   | Conversion Rate, Purchase Rate                   |
| **Budget Metrics**       | Total Budget, Avg Budget per Campaign            |

Problem Statement 2: Charts Requirement
| Visualization                     | Description                                  |
| --------------------------------- | -------------------------------------------- |
| **Gender – Donut Chart**          | Shows performance split by target gender     |
| **Age Group – Bar Chart**         | Displays engagement by age groups            |
| **Country – Map Chart**           | Shows geographic distribution of performance |
| **Calendar Heatmap**              | Displays monthly activity trends             |
| **Weekly Trend – Stacked Column** | Weekly comparison based on ad type           |
| **Hourly Trend – Area Chart**     | Hourly engagement patterns                   |
| **Ad Type – Matrix Table**        | Performance comparison across ad formats     |

## 📊 Performance KPI Overview

| 📌 KPI | 📖 Definition | 🧮 Formula (Conceptual) | 🎯 Purpose |
|-------|---------------|-------------------------|-----------|
| 👁️ **Impressions** | Number of times ads were shown | Count of `event_type = Impression` | Measure reach |
| 👆 **Clicks** | Number of times users clicked ads | Count of `event_type = Click` | Measure engagement intent |
| 🔁 **Shares** | Number of times ads were shared | Count of `event_type = Share` | Viral engagement |
| 💬 **Comments** | Number of comments on ads | Count of `event_type = Comment` | User sentiment & feedback |
| 🛒 **Purchases** | Number of purchases driven by ads | Count of `event_type = Purchase` | Conversions |
| 🎯 **Engagements** | Total interactions | Clicks + Shares + Comments | Engagement volume |
| 📈 **CTR** | % of impressions that became clicks | (Clicks ÷ Impressions) × 100 | Ad effectiveness |
| 💥 **Engagement Rate** | % of impressions that became engagements | (Engagements ÷ Impressions) × 100 | Overall ad appeal |
| 🔄 **Conversion Rate** | % of clicks that became purchases | (Purchases ÷ Clicks) × 100 | Funnel efficiency |
| 🧾 **Purchase Rate** | % of impressions that became purchases | (Purchases ÷ Impressions) × 100 | Conversion from reach |
| 💰 **Total Budget** | Total spend across campaigns | Σ `campaigns.total_budget` | Cost & budget analysis |
| 📊 **Avg. Budget / Campaign** | Average budget per campaign | Total Budget ÷ Campaign Count | Budget distribution |

## 📊 5. Dashboard Pages
  A. Instagram Page
    - Displays all KPI cards, demographic visuals, geographic analysis, and performance insights.
<img width="1271" height="730" alt="image" src="https://github.com/user-attachments/assets/cd50f909-c5c4-428d-a34b-7386933764e1" />


  B. Detailed Page
    - Transaction-level view showing event records, user info, and campaign details.

<img width="1327" height="731" alt="image" src="https://github.com/user-attachments/assets/ae61f292-56b9-4a28-9372-6e0d04240b34" />

## 🧠 6. Dashboard Insights
🔹 Top Funnel: Strong Awareness
  - 216K impressions indicate huge reach
  - CTR of 11.76% → extremely strong (industry avg 1–2%)

🔹 Mid Funnel: High Engagement
  - Engagement rate: 13.56%
  - Users actively like/click/share/comment

🔹 Bottom Funnel: Weak Conversion
  - Purchase Rate only 0.61%
  - Indicates leakage in conversion funnel
✔ Possible causes: Poor landing page, user mismatch, weak offer

🔹 Demographic Insights
  - Females engage more than males (43% vs 22%)
  - Age 18–30 generates maximum response

🔹 Geographic Insights
  Highest engagement: India, US, Brazil
  High-value markets: Germany, UK

🔹 Time-Based Patterns
  Engagement peaks in afternoon & evening
  Calendar shows engagement spikes during promotional periods

## 📁 8. Download Project Files
| File Type                | Link              |
| ------------------------ | ----------------- |
| 📊 Power BI Dashboard    | *([Download Dashboard](https://github.com/Prabhakar620126/Instagram_Fackbook_Dashboard/blob/main/instagram%20and%20facebook%20dashboad.pbit)* |
| 📄 ad_event          | *([Download](https://github.com/Prabhakar620126/Instagram_Fackbook_Dashboard/blob/main/ad_events.csv))* |
| 📄 ads      | *([Download](https://github.com/Prabhakar620126/Instagram_Fackbook_Dashboard/blob/main/ads.csv))* |
| 📄 Campaigns    | *([Download](https://github.com/Prabhakar620126/Instagram_Fackbook_Dashboard/blob/main/campaigns.csv))* |
| 📄 Users | *([Download](https://github.com/Prabhakar620126/Instagram_Fackbook_Dashboard/blob/main/users.csv))* |

## 📌 9. Conclusion
  - This Meta Ad Performance Dashboard helps businesses:
  - Identify high-performing audiences
  - Optimize ad spend
  - Improve campaign ROI
  - Understand engagement patterns
  - Strengthen conversion funnel efficiency

# 🙌 Author  
**PRABHAKAR KUMAR SHAHI**  
📧 Email: prabhakar620126@gmail.com 
🔗 GitHub: https://github.com/Prabhakar620126
