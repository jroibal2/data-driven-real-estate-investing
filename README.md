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

![heatmap](./outputs/heatmap_example.png)
![top10](./outputs/top10_bar_chart.png)

| Address                         | Price     | Acres | $/Acre  |
|----------------------------------|-----------|--------|----------|
| 1234 Rio Rancho Blvd, NM         | $22,000   | 1.0    | $22,000  |
| 5678 Vista Del Norte, NM         | $17,000   | 0.8    | $21,250  |

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
