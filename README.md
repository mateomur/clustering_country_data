# Clustering Analysis of Country Data

## 📄 Description
This repository contains a Jupyter Notebook in which we perform a complete clustering analysis on the **Country Data** dataset from Kaggle. We clean and preprocess socio‑economic indicators (GDP per capita, life expectancy, health expenditure, infant mortality rate, etc.), explore the data, and apply four clustering algorithms—**K‑Means**, **Agglomerative Clustering**, **DBSCAN**, and **Spectral Clustering**—to identify natural groupings of countries based on their development profiles.

---

## 🗂️ Table of Contents
- [Dataset](#dataset)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Project Structure](#project-structure)  
- [Data Preparation](#data-preparation)  
- [Exploratory Data Analysis](#exploratory-data-analysis)  
- [Variables for Clustering](#variables-for-clustering)  
- [Clustering Methods](#clustering-methods)  
  - [K‑Means](#k‑means)  
  - [Agglomerative Clustering](#agglomerative-clustering)  
  - [DBSCAN](#dbscan)  
  - [Spectral Clustering](#spectral-clustering)  
- [Results and Discussion](#results-and-discussion)  
- [Conclusion](#conclusion)  

---

## 📊 Dataset
The **Country Data** dataset contains the following socio‑economic indicators for 167 countries:

- **child_mort**: Infant mortality rate (deaths per 1,000 live births)  
- **exports**: Exports (% of GDP)  
- **health**: Health expenditure (% of GDP)  
- **imports**: Imports (% of GDP)  
- **income**: Income per capita  
- **inflation**: Annual inflation rate (%)  
- **life_expec**: Life expectancy (years)  
- **total_fer**: Total fertility rate (children per woman)  
- **gdpp**: GDP per capita  

These variables let us compare countries’ development levels and socioeconomic conditions.

---

## 💻 Installation

1. **Clone this repository**  
   ```bash
   git clone https://github.com/mateomur/clustering_country_data.git
   cd clustering_country_data
