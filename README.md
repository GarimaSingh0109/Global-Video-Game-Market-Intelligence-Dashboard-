
# 🎮  Global-Video-Game-Market-Intelligence-Dashboard-

> An interactive Power BI dashboard analyzing global video game sales across platforms, genres, publishers, and regions — built on a dataset of **51,646 games** from **3,385 publishers**, totalling **₹5,080.71 Million** in global sales.

---

## 📊 Dashboard Overview

The dashboard provides a comprehensive view of the video game market through six key visualizations, a dynamic filter panel, and a live insights panel.

| Section | Description |
|---|---|
| **Global Sales Over Time** | Line chart tracking physical retail sales from 1971 to 2023 |
| **Top 10 Best Selling Games** | Bar chart of all-time bestsellers by global units sold |
| **Sales By Console** | Platform comparison across DS, GBA, PS, PS2, PS3, PS4, PSP, Wii, X360, XB |
| **Sales By Genre** | Horizontal bar chart ranking Sports, Shooter, Racing, Misc, and Action |
| **Genre Performance Across Regions** | Multi-line chart comparing NA, JP, and PAL sales per genre |
| **Insights & Recommendations** | Static panel summarising the 5 key strategic findings |

---

## 🗂️ Dataset

| Metric | Value |
|---|---|
| Total Games | 51,646 |
| Total Publishers | 3,385 |
| Total Global Sales | ₹5,080.71 Million |
| Average Critic Score | 7.20 / 10 |
| Year Range | 1971 – 2023 |

> **Note:** Sales figures represent **physical retail** only. Digital distribution (Steam, PSN, Xbox Store) is not included, which significantly underrepresents post-2013 market activity.

---

## 🔍 Key Insights & Recommendations

**1. Fix the data gap** — Integrate digital sales (Steam, PSN, Xbox) since the post-2013 cliff reflects missing data, not a real market collapse.

**2. Consolidate platform bets** — PS2's 1.7× lead (₹959.97M) proves platform concentration drives outsized revenue; identify and lock in today's equivalent dominant platform.

**3. Go all-in on Sports & Action for NA/PAL** — Top genres + top regions = highest ROI; deprioritize or localize separately for Japan.

**4. Chase open-world deals** — GTA V at 39.71M units (2× the next title) proves the open-world formula is the only reliable path to breakout sales.

**5. Allocate budgets by region signal** — NA first, PAL second, Japan last; the regional gap is a resource allocation guide, not a problem to fix.

---

## 🎛️ Filters

The left-hand panel supports dynamic filtering by:

- **Publisher** — filter by individual publisher (e.g. AAA, Abbey Games, Absolute Entertainment)
- **Genre** — Action, Action-Adventure, Adventure, Board Game, Education, Fighting, Misc, MMO
- **Console** — SAT, 2600, 3DO, 3DS, 5200, 7800, Ace, ACPC, and more

All charts update dynamically when filters are applied.

---

## 🏆 Top 10 Best Selling Games

| Rank | Game | Sales (M) |
|---|---|---|
| 1 | Grand Theft Auto V | 39.71 |
| 2 | Red Dead Redemption 2 | 24.01 |
| 3 | Minecraft | 16.19 |
| 4 | Grand Theft Auto: Vice City | 14.82 |
| 5 | Call of Duty: Modern Warfare | 17.65 |
| 6 | Call of Duty: Modern Warfare 2 | 14.82 |
| 7 | Call of Duty: Ghosts | 13.53 |
| 8 | Call of Duty: Black Ops II | 14.28 |
| 9 | Call of Duty: Black Ops 3 | 15.09 |
| 10 | Call of Duty: Black Ops | 14.74 |

---

## 🕹️ Platform Sales Summary

| Console | Sales (₹ Million) |
|---|---|
| PS2 | 959.97 |
| PS | 538.98 |
| PS3 | 523.46 |
| X360 | 523.74 |
| DS | 380.53 |
| PS4 | 473.8 |
| Wii | 361.52 |
| GBA | 200.11 |
| PSP | 189.97 |
| XB | 129.35 |

---

## 🌍 Regional Performance

| Region | Strength |
|---|---|
| **North America (NA)** | Dominant across all genres |
| **PAL (Europe/Australia)** | Strong second — closely tracks NA |
| **Japan (JP)** | Consistently lowest; distinct genre preferences |

---

## 🛠️ Built With

- **Power BI Desktop** — dashboard design and interactivity
- **DAX** — calculated measures and KPIs
- **Power Query** — data cleaning and transformation

---

## 📁 Repository Structure

```
📦 vg-sales-dashboard
 ┣ 📊 VideoGameSales.pbix       # Power BI dashboard file
 ┣ 📄 vgsales.csv               # Raw dataset
 ┣ 🖼️ dashboard_preview.png     # Dashboard screenshot
 ┗ 📖 README.md                 # This file
```

---

## 🚀 Getting Started

1. Clone this repository
   ```bash
   git clone https://github.com/your-username/vg-sales-dashboard.git
   ```
2. Open `VideoGameSales.pbix` in **Power BI Desktop**
3. If prompted, refresh the data source and point it to `vgsales.csv`
4. Use the left-hand filter panel to explore by publisher, genre, or console

---

## 📌 Notes

- All monetary values are in **Indian Rupees (₹)** as displayed in the dashboard
- Critic scores are sourced from Metacritic aggregates where available
- Post-2013 data should be treated with caution due to the digital sales gap

---

## 📜 License

This project is for educational and analytical purposes. Dataset sourced from publicly available video game sales records.
