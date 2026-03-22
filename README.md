### Olist E-Commerce: What's Driving Bad Reviews & How to Fix It
> A data-driven analysis of delivery performance, seller quality, and 
> customer satisfaction using 96,478 real orders from Brazil's largest 
> e-commerce marketplace.

---

## 🎯 Key Product Insight
Delivery delays are the dominant driver of customer dissatisfaction on Olist.
Orders delayed 7+ days show a 60% drop in ratings (4.29 → 1.71). A small 
subset of sellers and regions disproportionately contribute to these delays, 
making them the highest-leverage targets for improving customer satisfaction 
and retention.

Improving delivery reliability represents the highest-impact lever for 
increasing customer satisfaction on the platform.

---

## 📊 Business Problem
Olist wants to understand why customers leave bad reviews and what can 
be done to improve satisfaction scores across the platform.

---

## 🔍 Key Findings

| # | Finding | Impact |
|---|---------|--------|
| 1 | Orders taking 21+ days score 3.01 vs 4.41 for under 7 days | 32% score drop |
| 2 | Orders arriving 7+ days late score just 1.71 vs 4.29 for early | 60% score drop |
| 3 | North/Northeast states average 20+ delivery days | Regional gap |
| 4 | Office furniture takes 20.4 days avg — worst category | Bulky item problem |
| 5 | Top bad sellers average 2.27 score despite normal delivery time | Quality issue |
| 6 | Payment method has minimal impact on satisfaction | Not a priority |

---

## 📸 Key Visualizations

### Delivery Delay vs Review Score
![Delay vs Rating](https://github.com/user-attachments/assets/25843a6f-0147-4c57-bf41-e3735fe34779)
)
> Orders delayed beyond 7 days show a sharp decline in customer satisfaction, 
> confirming delivery reliability as the key driver of ratings.

### Regional Delivery Performance
![Region vs Delivery](https://github.com/user-attachments/assets/805134fe-b267-471c-84d1-556403e744fe)
)
> North/Northeast states average 20+ delivery days, representing the highest 
> priority regions for logistics improvement.

---

## 💡 Recommendations
1. Enforce SLA penalties on top 10 worst-performing sellers → Expected to significantly reduce delayed orders and improve platform-wide ratings
2. Introduce ETA accuracy as a core KPI → Meeting delivery promises matters more than speed; reduces very late orders scoring 1.71
3. Target AL, PA, MA, CE, BA states for logistics infrastructure improvement → These states average 20+ days, directly hurting satisfaction
4. Implement seller scorecard with minimum 3.5 score threshold → Removes low-quality sellers disproportionately damaging platform reputation
5. Introduce category-specific delivery SLAs for bulky products → Office furniture averaging 20.4 days needs dedicated handling

---

## 🛠️ Tools Used
- Python, Pandas
- SQLite (via sqlite3)
- Matplotlib, Seaborn
- Google Colab

---

## 📁 Dataset
[Olist Brazilian E-Commerce Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) — Kaggle

---

## ▶️ How to Run
1. Clone this repository
2. Upload all CSV files to Google Colab
3. Open and run `olist_analysis.ipynb` cell by cell

---

## 👤 Author
**Viraj** | AI & ML Student | NHCE Bangalore  
[LinkedIn](https://www.linkedin.com/in/viraj-prabhu-61b45933b/) | [GitHub](https://github.com/Viraj5216)
