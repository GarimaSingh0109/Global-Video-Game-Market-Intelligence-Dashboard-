# 🎮 Global-Video-Game-Market-Intelligence-Dashboard

> An interactive **Excel dashboard** analyzing global video game sales across platforms, genres, publishers, and regions — built on a dataset of **51,646 games** from **3,385 publishers**, totalling **₹5,080.71 Million** in global sales.

---

## 📊 Dashboard Overview

The dashboard is built entirely in **Microsoft Excel** using pivot tables, slicers, and native Excel charts — no external tools or add-ins required.

| Section | Chart Type | Description |
|---|---|---|
| **Global Sales Over Time** | Line Chart | Physical retail sales trend from 1971 to 2023 |
| **Top 10 Best Selling Games** | Column Chart | All-time bestsellers by global units sold |
| **Sales By Console** | Column Chart | Platform comparison across DS, PS2, PS3, PS4, Wii, X360 and more |
| **Sales By Genre** | Horizontal Bar | Sports, Shooter, Racing, Misc, and Action ranked by volume |
| **Genre Performance Across Regions** | Multi-Line Chart | NA, JP, and PAL sales compared per genre |
| **Insights & Recommendations** | Text Box | 5 strategic findings embedded directly in the dashboard |

---

## 🗂️ Dataset

| Metric | Value |
|---|---|
| Total Games | 51,646 |
| Total Publishers | 3,385 |
| Total Global Sales | ₹5,080.71 Million |
| Average Critic Score | 7.20 / 10 |
| Year Range | 1971 – 2023 |

> **Note:** Sales figures represent **physical retail** only. Digital distribution (Steam, PSN, Xbox Store) is not captured, which significantly underrepresents post-2013 market activity.

---

## 📁 Repository Structure

```
📦 vg-sales-dashboard
 ┣ 📊 VideoGameSales.xlsx        # Excel dashboard (main file)
 ┣ 📄 vgsales.csv                # Raw source dataset
 ┣ 🖼️ dashboard_preview.png      # Dashboard screenshot
 ┗ 📖 README.md                  # This file
```

---

## 🚀 Getting Started

1. Clone this repository
   ```bash
   git clone https://github.com/your-username/vg-sales-dashboard.git
   ```
2. Open `VideoGameSales.xlsx` in **Microsoft Excel** (2016 or later recommended)
3. If prompted, click **Enable Content** to allow slicers and pivot tables to refresh
4. Use the **Publisher**, **Genre**, and **Console** slicers on the left panel to filter all charts dynamically

---

## 🎛️ Filters (Slicers)

The left-hand panel contains three Excel slicers for interactive filtering:

- **Publisher** — e.g. AAA, Abbey Games, Absolute Entertainment, Activision
- **Genre** — Action, Action-Adventure, Adventure, Board Game, Education, Fighting, Misc, MMO
- **Console** — SAT, 2600, 3DO, 3DS, 5200, 7800, Ace, ACPC, and more

All charts and KPI cards update instantly when a slicer selection is changed.

---

## 📌 KPI Cards (Header)

| KPI | Value |
|---|---|
| Total Global Sales | ₹5,080.71 Million |
| Total Games | 51,646 |
| Total Publishers | 3,385 |
| Average Critic Score | 7.20 / 10 |

---

## 🏆 Top 10 Best Selling Games

| Rank | Game | Sales (M units) |
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
| PS4 | 473.80 |
| Wii | 361.52 |
| GBA | 200.11 |
| PSP | 189.97 |
| XB | 129.35 |

---

## 🌍 Regional Performance

| Region | Performance |
|---|---|
| **North America (NA)** | Dominant across all genres |
| **PAL (Europe / Australia)** | Strong second — closely tracks NA |
| **Japan (JP)** | Consistently lowest; distinct genre preferences |

---

## 🔍 Key Insights & Recommendations

**1. Fix the data gap** — Integrate digital sales (Steam, PSN, Xbox) since the post-2013 cliff reflects missing data, not a real market collapse.

**2. Consolidate platform bets** — PS2's 1.7× lead (₹959.97M) proves platform concentration drives outsized revenue; identify and lock in today's equivalent dominant platform.

**3. Go all-in on Sports & Action for NA/PAL** — Top genres + top regions = highest ROI; deprioritize or localize separately for Japan.

**4. Chase open-world deals** — GTA V at 39.71M units (2× the next title) proves the open-world formula is the only reliable path to breakout sales.

**5. Allocate budgets by region signal** — NA first, PAL second, Japan last; the regional gap is a resource allocation guide, not a problem to fix.

---

## 🛠️ Built With

- **Microsoft Excel** — pivot tables, slicers, charts, and dashboard layout
- **Power Query** *(optional)* — data cleaning and import from CSV

---

## ⚙️ Requirements

- Microsoft Excel **2016 or later** (for slicer and pivot table compatibility)
- Macros do **not** need to be enabled — the dashboard uses only native Excel features

---

## 📜 License

This project is for educational and analytical purposes. Dataset sourced from publicly available video game sales records.
