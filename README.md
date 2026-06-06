# Task 3: Website Traffic Sources Analysis

## 🏢 Internship Details
| Field | Details |
|-------|---------|
| **Company** | Codtech IT Solutions Private Limited |
| **Domain** | Data Analytics |
| **Intern Name** | MD SAHIL ANSARI |
| **Intern ID** | CITS3147 |
| **Task** | Task 3 – Website Traffic Sources |

---

## 📌 Objective
To analyze website traffic data across multiple traffic channels and extract meaningful insights about:
- Which traffic sources drive the most sessions and revenue
- Conversion and bounce rate performance per source
- Device and geography distribution of users
- Weekly traffic patterns and trends over time

---

## 📁 Files in This Repository

| File | Description |
|------|-------------|
| `website_traffic_sources.csv` | 14-day traffic dataset with 84 records across 6 sources |
| `website_traffic_analysis.ipynb` | Jupyter Notebook with full analysis and visualizations |
| `README.md` | Project documentation |

---

## 📊 Dataset Description

The dataset contains **84 records** across **16 columns**, covering 6 traffic sources over 14 days:

| Column | Description |
|--------|-------------|
| Date | Date of the record |
| TrafficSource | Channel: Organic Search, Paid Search, Social Media, Direct, Referral, Email |
| Sessions | Total number of sessions |
| Users | Total unique users |
| NewUsers | First-time visitors |
| Bounces | Sessions with only one page view |
| BounceRate | Percentage of bounced sessions |
| PageViews | Total pages viewed |
| PagesPerSession | Average pages per session |
| AvgSessionDuration | Average session length in seconds |
| Conversions | Completed goals/purchases |
| ConversionRate | Percentage of sessions that converted |
| Revenue | Revenue generated (₹) |
| Device | Desktop / Mobile / Tablet |
| Country | Visitor's country |
| Campaign | Campaign name or type |

---

## 📈 Analysis Performed

1. **Traffic Source Overview** – Sessions and share by source (bar + pie chart)
2. **Daily Traffic Trend** – Line chart of sessions over 14 days
3. **Conversion Rate** – Bar chart by traffic source with color indicators
4. **Revenue Analysis** – Bar chart and stacked area chart over time
5. **Bounce Rate & Session Duration** – Side-by-side comparison
6. **Device Distribution** – Pie chart and revenue by device
7. **Country Analysis** – Horizontal bar chart by country
8. **Day-of-Week Heatmap** – Avg sessions by source and weekday
9. **Correlation Heatmap** – Relationships between traffic metrics

---

## 🛠️ Technologies Used

- **Language:** Python 3
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Tool:** Jupyter Notebook

---

## 🚀 How to Run

1. Clone or download this repository
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```
3. Place `website_traffic_sources.csv` in the same folder as the notebook
4. Open the notebook:
   ```bash
   jupyter notebook website_traffic_analysis.ipynb
   ```
5. Run all cells: **Kernel → Restart & Run All**

---

## 💡 Key Insights

- **Organic Search** drives the highest traffic volume — SEO is critical
- **Paid Search & Email** deliver the best conversion rates (~10%)
- **Social Media** has the highest bounce rate — landing pages need optimization
- **Mobile** is the dominant device across all sources
- **Weekdays** show peak traffic, ideal for campaign scheduling

---

*This project was completed as part of the Codtech IT Solutions Data Analytics Virtual Internship.*
