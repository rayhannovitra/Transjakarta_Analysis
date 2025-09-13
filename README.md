# Public Transportation Analysis (Transjakarta)
End-to-end data analysis of Transjakarta ridership, from cleaning raw data in Excel, exploring metrics with SQLite in Google Colab, to building an interactive Power BI dashboard. Discover patterns in trips, revenue, and passenger demographics.

## Project Structure
```bash
├── data/
│   └── dfTransjakarta_clean.csv       # Dataset hasil data cleaning
├── notebook/
│   └── Analysis_Transjakarta.ipynb    # Analisis SQLite via Google Colab
├── powerbi/
│   └── Dashboard_Transjakarta.pbix    # File dashboard Power BI
├── images/
│   └── Dashboard_Preview.png          # Screenshot dashboard
└── README.md
```

## Tools and Technologies
- Data Source: Kaggle (Transjakarta - Public Transportation Transaction)
- Data Cleaning: Excel
- Data Analysis: SQLite (Google Colab)
- Data Visualization: Power BI

## Metrics Analyzed
1. Total Trips per Day
2. Trips by Hour (Peak Hours)
3. Top 10 Corridors by Trips
4. Top 10 Corridors by Revenue
5. Paid vs Unpaid Trips
6. Gender Distribution
7. Average Trip Duration
8. Weekday vs Weekend Trips
9. Age Group Distribution
10. Top 10 Tap-In Stops

## Insights
1. Ridership peaks on weekdays during morning & evening rush hours
2. Cibubur - Balai Kota is the busiest corridor by trips and revenue
3. ~45% of trips have payAmount = 0 (unpaid trips)
4. Majority passengers are aged 30–39 with a near-balanced gender distribution
5. Average trip duration is around 72 minutes

## Dashboard Preview
![Dashboard Preview]()
