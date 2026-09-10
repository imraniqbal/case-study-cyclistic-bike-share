# Cyclistic Bike-Share: Data Analysis Case Study

An end-to-end data analysis project exploring 12 months of historical trip data to uncover behavioral differences between casual riders and annual members, aimed at driving marketing conversion strategies.

## 📊 Project Overview
As part of the Google Data Analytics Professional Certificate curriculum, this case study investigates **Cyclistic** (a fictional bike-share company in Chicago with over 5,800 bicycles and 600 docking stations). The primary business goal defined by Director of Marketing Lily Moreno is to maximize annual memberships, as annual members are significantly more profitable than casual riders. 

Instead of targeting brand-new customers, this project evaluates a high-conversion opportunity: converting existing casual riders—who are already familiar with the service—into dedicated annual members.

---

## 🛠️ The 6-Step Data Analysis Process
This project follows the industry-standard framework:
1. **Ask:** Define the core business question: *"How do annual members and casual riders use Cyclistic bikes differently?"*
2. **Prepare:** Collected 12 consecutive months of historical trip data (September 2025 – August 2026), addressing raw naming convention anomalies to maintain timeline continuity.
3. **Process:** Handled large-scale data manipulation ($\approx$6.1 million rows) using **Python (Pandas)**, cleaning anomalies, converting datetime objects, and generating custom columns (`ride_length` and `day_of_week`).
4. **Analyze:** Conducted descriptive statistics (mean, max, mode) to isolate behavioral patterns across user segments.
5. **Share:** Visualized findings using **Matplotlib** and **Seaborn** to highlight duration and weekly usage trends.
6. **Act:** Formulated data-driven strategic marketing recommendations for executive stakeholders.

---

## 📈 Key Findings & Insights
* **Ride Duration:** Casual riders take significantly longer trips on average (**~20.7 minutes**) compared to annual members (**~12.4 minutes**), indicating recreational and leisure use.
* **Usage Timing:** Annual members exhibit predictable weekday commuting spikes (peaking mid-week), whereas casual riders usage peaks heavily during weekends.

---

## 💡 Strategic Recommendations
1. **Weekend Digital Promotions:** Introduce app-based weekend bundle passes targeted frequently at active casual riders.
2. **Leisure-to-Member Credits:** Offer promotional credits where weekend leisure ride fees can be applied toward purchasing an annual membership.
3. **Targeted QR-Code Campaigns:** Place digital marketing touchpoints near high-traffic Chicago recreational docking stations.

---

## 🚀 Repository Contents
*[./case-study-cyclistic-bike-share.ipynb](https://www.kaggle.com/code/imran495/cyclistic-bike-share-data-analysis-case-study): The complete, executable Jupyter Notebook containing all data wrangling, cleaning, and visualization code hosted directly from Kaggle.
