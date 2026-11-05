# 🏛️ Washington, D.C. National Parks Visitation Analysis

## About the project

This project uses Python to explore recreation visits to National Park Service sites in the Washington, D.C. area. The goal is to understand which sites receive the most visits, when visitation is highest, and how visitation has changed over time.

## Questions explored

- Which sites had the most recreation visits in 2025?
- Which months were the busiest?
- How has visitation changed from 1979 to 2025?

## Tools used

Python · pandas · Plotly Express · Jupyter Notebook

## Data source

Data comes from the **National Park Service (NPS)**. You can explore visitation reports using the [NPS Public Use Statistics Query Builder](https://irma.nps.gov/Stats/SSRSReports/National%20Reports/Query%20Builder%20for%20Public%20Use%20Statistics%20%281979%20-%20Last%20Calendar%20Year%29).

### Data dictionary

| Column | Description |
|---|---|
| `ParkName` | Name of the NPS site |
| `RecreationVisits` | Number of recorded recreation visits |
| `Month` | Month of visitation (monthly dataset) |
| `Year` | Year of visitation (historical dataset) |

The analysis uses three datasets: 2025 visits by site, 2025 monthly visits, and annual visits from 1979–2025. Recreation visits count visits, not necessarily unique people.

## View the analysis

Open **[dc_national_parks_analysis.ipynb](dc_national_parks_analysis.ipynb)** to see the Python code, visualizations, and findings.
