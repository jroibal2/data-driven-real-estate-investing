# data-driven-real-estate-investing
A python code created for data driven real estate investing. Rio Rancho New Mexico Case Study Example.

# 🏡 Data-Driven Real Estate Investing: A Case Study in Rio Rancho, NM

## 📈 Project Overview

This project demonstrates how publicly available data and Python-based analysis can be used to identify **undervalued land parcels** in **Rio Rancho, New Mexico**. It combines geographic information, Zillow listings, price-per-acre calculations, and spatial analysis to generate actionable insights for investors and homebuyers.

The goal: **Financial Independence through smarter, data-backed real estate investing.**

---

## 🎯 Objectives

- Identify areas with **high real estate transaction activity**
- Analyze land listings to find those with **low price per acre**
- Visualize patterns using maps and KDE heatmaps
- Filter and rank opportunities based on investment potential
- Automate and document the process for repeatable insights

---

## 🛠️ Tools & Technologies

- **Python** (Colab-friendly)
- `pandas`, `geopandas`, `matplotlib`, `seaborn`, `folium`, `scipy`
- Zillow scraped CSV data (current listings + historical sales)
- Kernel Density Estimation for heatmaps
- Spatial joins and shapefiles for GIS overlays

---

## 📊 Key Features

- 📍 **Price-per-Acre Calculation**: Normalize lot sizes (acres vs sqft) and identify best-value listings
- 🧭 **Heatmap of Sold Homes**: Visualize Rio Rancho’s most active sales regions
- 🗺️ **Shapefile Generation**: Extract polygon contours of high-sales zones
- 🧮 **Filtered Listings**: Only properties within “hot zones” are ranked
- 📊 **Top 10 Listings**: Easily identify the best-value land by address, price, and size

---

## 🧪 Sample Output

![heatmap](Rio_Rancho_Heat_Map_5282025.png)
![top10](./outputs/top10_bar_chart.png)

🏞️ Top 10 Cheapest Lots ($/Acre) Within High-Density Sale Zones (5/29/2025):
                                              address    price  lot_acres  price_per_acre
       LOT NULL Fifteen B Dr NE, Rio Rancho, NM 87144 150000.0       2.72    55147.058824
               550B Fruta Rd NE, Rio Rancho, NM 87124 155000.0       2.50    62000.000000
         1522 Broadmoor Blvd NE, Rio Rancho, NM 87144  42950.0       0.50    85900.000000
3200 Stapleton Ave NE LOT 4A-4B, Rio Rancho, NM 87124  99000.0       1.00    99000.000000
         1814 Broadmoor Blvd NE, Rio Rancho, NM 87144 250000.0       2.50   100000.000000
                1250 Inca Rd NE, Rio Rancho, NM 87124 100000.0       1.00   100000.000000
         1526 Broadmoor Blvd NE, Rio Rancho, NM 87144  60000.0       0.50   120000.000000
               1990 12th Ave SE, Rio Rancho, NM 87124 120000.0       0.98   122448.979592
               2402 Istle Rd NE, Rio Rancho, NM 87124 110000.0       0.79   139240.506329
              2320 Idalia Rd NE, Rio Rancho, NM 87124  98750.0       0.62   159274.19354

---

## 📁 Project Structure

data-driven-real-estate-investing-roibal/
├── notebooks/
│ └── real_estate_analysis.ipynb
├── data/
│ └── RR_Land_For_Sale_5_29_2025.csv
├── shapefiles/
│ └── high_density_regions.*
├── outputs/
│ ├── top_10_listings.csv
│ └── heatmap_example.png
├── README.md
├── requirements.txt
└── LICENSE

---

## 📚 Report

A full PDF version of the project is available here:  
➡️ **[Download Full Report](./outputs/RioRancho_DataDrivenRealEstate.pdf)**

---

## 🚀 Next Steps

- Create a public dashboard or web app using Streamlit or Dash
- Integrate mortgage calculators and demographic data
- Scale the analysis to other fast-growing metro areas

---

## ⚠️ Disclaimer

> This project is provided for informational and educational purposes only. All analysis is based on publicly available data at the time of retrieval and is not intended as real estate, financial, or legal advice. The author makes no representations regarding the accuracy or applicability of the data to any specific transaction. Buyers and investors should always consult with licensed professionals — including real estate agents, attorneys, and financial advisors — before making any purchase or investment decisions.

---

## 📬 Contact

Created by **Joaquin Roibal**  
Connect with me on [LinkedIn](https://www.linkedin.com/in/joaquinroibal) or [Email](mailto:jroibal2@cnm.edu)  
