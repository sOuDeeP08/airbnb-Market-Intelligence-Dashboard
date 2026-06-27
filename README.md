# 🏠 Airbnb Market Intelligence Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Data Analysis](https://img.shields.io/badge/Data%20Analysis-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

A 3-page interactive Power BI dashboard analysing **2,79,712 Airbnb listings** across **10 global cities**, uncovering pricing trends, guest behaviour, city-level market share, and host trust patterns from **5.37 lakh+ reviews**.

---

## 📌 Project Overview

This end-to-end business intelligence project transforms raw Airbnb listings and review data into actionable insights for hosts, investors, and platform strategists. The dashboard covers the full Airbnb growth story — from its 2008 launch through the COVID-19 impact — and benchmarks performance across 10 major cities worldwide.

---

## 📊 Dashboard Pages

### Page 1 — Overview
- KPI cards: Total Listings (2,79,712), Cities (10), Hosts (1,82,024), Properties (144), Reviews (5.37L+)
- Time-series area chart tracking listing growth from **2008–2021** with annotated business phases: Introduction → Growth → Maturity → Decline → Reinvention → COVID-19
- Room type breakdown: Entire Place, Private Room, Hotel Room, Shared Room

### Page 2 — Ratings & Market Share
- Pareto-style bar chart showing **market share by city** — Paris, NYC & Sydney account for ~50% of all listings
- Superhost vs Non-Superhost listing comparison across cities
- Average nightly pricing by room type:
  - 🏨 Hotel Room: **$800.21**
  - 🏠 Entire Place: **$673.35**
  - 🛋️ Shared Room: **$579.92**
  - 🚪 Private Room: **$462.44**
- Cross-city ratings chart — Mexico City (94.8) and Rio de Janeiro (94.6) ranked highest; Hong Kong (89.7) and Istanbul (91.1) ranked lowest

### Page 3 — Reviews & Trust
- Review frequency distribution: **96.6% of guests reviewed only once**, 98.8% reviewed 3 or fewer times
- Seasonality heatmap across 5 cities — Paris & Rome peak Apr–Aug; New York surges Nov–Dec
- Host trust analysis: **66.9% of hosts are fully identity-verified** with a profile picture

---

## 💡 Key Insights

| Insight | Finding |
|---|---|
| Top market | Paris leads in listings & reviews; hotel rooms cost **2× Airbnb rates** |
| Best-rated cities | Mexico City & Rio de Janeiro (avg. 94.6–94.8 / 100) |
| Lowest-rated cities | Hong Kong & Istanbul — cleanliness & value-for-money score lowest |
| Guest behaviour | 96.6% of guests leave only 1 review ever |
| Peak season | European summer (Apr–Aug) dominates review volume |
| Host trust | 66.9% of hosts are identity-verified with profile picture |
| COVID-19 impact | Growth halted in 2019; new listings dropped sharply through 2020–21 |

---

## 🗂️ Dataset

> ⚠️ **Note:** The full dataset files exceed GitHub's 25MB upload limit and are not included in this repository.

### Download Full Dataset
| Source | Link |
|---|---|
| 🌐 Inside Airbnb (Original Source) | [insideairbnb.com/get-the-data](http://insideairbnb.com/get-the-data/) |

### Sample Files (included in this repo)
| File | Rows | Description |
|---|---|---|
| `Dataset/Listings_sample.csv` | 1,000 | Sample of listings data — pricing, room type, city, host info, ratings |
| `Dataset/Reviews_sample.csv` | 1,000 | Sample of reviews data — listing ID, reviewer ID, review date |
| `Dataset/Listings_data_dictionary.csv` | — | Column definitions for listings data |
| `Dataset/Reviews_data_dictionary.csv` | — | Column definitions for reviews data |

### Full Dataset Stats
| File | Records |
|---|---|
| Listings.csv | 2,79,712 listings |
| Reviews.csv | 5,37,300+ reviews |

---

## 🛠️ Tools & Skills Used

- **Power BI** — Data modelling, DAX measures, drill-through filters, interactive slicers
- **Data Cleaning** — Handling nulls, data type formatting, date parsing
- **Data Modelling** — Relationship mapping between Listings and Reviews tables
- **DAX** — Custom measures for KPIs, cumulative %, average ratings
- **Visual Design** — Multi-page layout, colour-coded storytelling, annotated charts

---

## 📁 Project Structure

```
airbnb-market-intelligence-dashboard/
│
├── 📂 Dataset/
│   ├── Listings.csv
│   ├── Reviews.csv
│   ├── Listings_data_dictionary.csv
│   └── Reviews_data_dictionary.csv
│
├── 📂 Dashboard/
│   └── Airbnb_Performance_Dashboard.pbix
│
├── 📂 Screenshots/
│   ├── overview.png
│   ├── ratings.png
│   └── reviews.png
│
└── README.md
```

---

## 📸 Dashboard Preview

| Overview | Ratings & Market Share | Reviews & Trust |
|---|---|---|
| ![Overview](Screenshots/overview.png) | ![Ratings](Screenshots/ratings.png) | ![Reviews](Screenshots/reviews.png) |

---

## 🚀 How to Open

### 📥 Download the Dashboard
> The `.pbix` file exceeds GitHub's upload limit. Download it directly from Google Drive:
>
> **[⬇️ Download Airbnb_Performance_Dashboard.pbix](https://drive.google.com/file/d/1PFkGhcxsdAkwE60kdSkyIRkAsipFQMO9/view?usp=drive_link)**

### Steps
1. Download the `.pbix` file from the link above
2. Open it in **Power BI Desktop** (free to download from Microsoft)
3. Download the sample dataset files from the `Dataset/` folder in this repo
4. If prompted, update the data source path to your local dataset folder
5. Refresh the data and explore the dashboard

---

## 👤 Author

**Soudeep Mazumder**  
📧 [soudeepmazumder2004@gmail.com]  
🔗 [https://www.linkedin.com/in/soudeep-mazumder-753a0324a/] 

---

## ⭐ If you found this useful, please star the repository!
