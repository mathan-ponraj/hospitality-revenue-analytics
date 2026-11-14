# Hospitality Revenue Optimization Analysis

A Power BI dashboard that shows where a multi-city hotel chain loses revenue and which cities, properties, and booking channels need attention.

[![GitHub](https://img.shields.io/badge/GITHUB-View%20Project-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mathan-ponraj/Hospitality-Revenue-Analysis)
<!-- [TODO: confirm the repo link. If you publish the dashboard online, add a LIVE DASHBOARD button here] -->

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Power Query](https://img.shields.io/badge/Power%20Query-217346?style=for-the-badge&logo=microsoft&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

## Problem Statement

Atliq Hotels, a multi-city hotel chain, had uneven occupancy across its cities and no clear view of why some properties did worse than others. Managers needed to see where revenue was lost to cancellations and no-shows, and how much each booking platform really earned.

## What I Built

In this project, I built an interactive Power BI dashboard that replaces manual reporting for Atliq Hotels. I organised the data in a star schema and wrote over 25 DAX measures for hotel KPIs such as RevPAR, ADR, and Occupancy %. Managers can filter by city, property, or booking platform to find where to improve.

## Key Features

- Tracks hotel KPIs: RevPAR, ADR, and Occupancy %.
- Filters by city, property, and booking platform.
- Shows revenue lost to cancellations and no-shows.
- Compares booking platforms, including Online Travel Agencies (OTAs).
- Shows demand patterns, such as weekdays and weekends.
- Finds cities and properties with low occupancy.

## Tech Stack

| Area              | Tools                    |
| ----------------- | ------------------------ |
| Dashboard         | Power BI                 |
| Data preparation  | Power Query              |
| Calculations      | DAX                      |
| Data model        | Star schema              |
| Version control   | Git, GitHub              |

## Project Structure

```text
Hospitality-Revenue-Analysis/
│
├── Dataset/            # Source data files
├── Dashboard/          # Power BI dashboard file
├── screenshots/        # Dashboard images
└── README.md           # Project documentation
```

<!-- [TODO: replace this tree with your real folders and file names, and add one line per file] -->

## Data

- **Source:** [TODO: add the dataset name and where you got it. If it is a practice dataset, say so]
- **Size:** [TODO: add the number of rows in the bookings table and the date range]
- **Data model:** Star schema.
  - **Fact tables:** Bookings and revenue.
  - **Dimension tables:** Cities, dates, and room categories.
- **Why a star schema:** Separating facts from dimensions keeps the model fast and makes it easy to filter and report.
- **Main columns:** [TODO: list the main columns, such as booking status, platform, check-in date, and revenue]
- **Cleaning steps:** Data was prepared with Power Query. [TODO: add the exact steps, such as fixing data types, removing duplicates, or handling missing values]

## Approach / Methodology

1. Loaded and prepared the data with Power Query.
2. Built a star schema with fact tables for bookings and revenue, and dimension tables for cities, dates, and room categories.
3. Wrote over 25 DAX measures for KPIs such as RevPAR, ADR, and Occupancy %.
4. Designed a multi-level dashboard with filters for city, property, and booking platform.
5. Built views that measure revenue lost to cancellations and no-shows.
6. Compared booking platforms to see which ones bring volume and which ones cost more in commission.
7. Looked at demand by day type and occupancy by city.

**KPI definitions:**

- **Occupancy %:** rooms sold divided by rooms available, times 100.
- **ADR (Average Daily Rate):** room revenue divided by rooms sold.
- **RevPAR (Revenue Per Available Room):** room revenue divided by rooms available.

## Results and Insights

- **Demand trends:** Weekend demand is much higher than weekday demand. This points to dynamic pricing or weekday promotions.
- **Channel profitability:** OTAs bring high volume, but their commission costs reduce profit. This points to the need for more direct bookings.
- **Occupancy imbalance:** Some cities have low occupancy again and again, which shows where marketing should focus.
- Total revenue: [TODO: add the number from your dashboard]
- Overall occupancy %: [TODO: add the number]
- RevPAR and ADR: [TODO: add the numbers]
- Revenue lost to cancellations and no-shows: [TODO: add the number]
- Weekend vs weekday occupancy: [TODO: add the numbers behind the insight]
- Cities with the lowest occupancy: [TODO: name them]

## How to Run Locally

You need Power BI Desktop, which is free and runs on Windows.

Clone the repository:

```bash
git clone https://github.com/mathan-ponraj/Hospitality-Revenue-Analysis.git
```

Go to the project folder:

```bash
cd Hospitality-Revenue-Analysis
```

Then open the `.pbix` file in the `Dashboard` folder with Power BI Desktop.

If Power BI cannot find the data, go to **Transform data > Data source settings** and point it to the files in the `Dataset` folder on your computer.

<!-- [TODO: add the exact .pbix file name and confirm how it connects to the data] -->

## Screenshots

| Dashboard overview | KPIs |
| ------------------ | ---- |
| ![Overview](screenshots/overview.png) | ![KPIs](screenshots/kpis.png) |

| Revenue leakage | Booking platforms |
| --------------- | ----------------- |
| ![Leakage](screenshots/revenue-leakage.png) | ![Platforms](screenshots/platforms.png) |

<!-- [TODO: add your screenshots to a screenshots/ folder with these file names, or update the paths] -->

## What I Learned and Future Improvements

**What I learned**

- Designed a star schema with fact and dimension tables.
- Wrote DAX measures for hospitality KPIs such as RevPAR, ADR, and Occupancy %.
- Prepared data with Power Query.
- Built a dashboard with filters so managers can explore the data on their own.
- Measured revenue lost to cancellations and no-shows.
- Turned the numbers into clear business points, such as weekend demand and OTA costs.

**Future improvements**

- Publish the dashboard online and add a live link.
- Add a forecast of future demand and occupancy.
- Test how much dynamic pricing could change revenue, using the data.

## Contact

[![GitHub](https://img.shields.io/badge/GitHub-mathan--ponraj-181717?style=for-the-badge&logo=github)](https://github.com/mathan-ponraj)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-mathan03-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/mathan03/)

---

Developed by Mathan
