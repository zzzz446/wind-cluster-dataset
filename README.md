# 🌬️ Wind Farm Cluster Datasets

This repository provides the open-source wind farm cluster datasets used in our research.

The datasets cover wind farms located in **China's eastern coastal region** and **Pakistan**, including historical power generation and meteorological observations at different temporal resolutions.

---

## 📊 Dataset Overview

| Dataset                        | Region                | Wind Farms | Power Data                         | Meteorological Variables | Time Period                  | Resolution |
| ------------------------------ | --------------------- | ---------: | ---------------------------------- | -----------------------: | ---------------------------- | ---------- |
| **China Wind Farm Cluster**    | Eastern Coastal China |          5 | Actual power generation            |                       10 | Jan. 3, 2022 – Apr. 30, 2023 | 15 min     |
| **Pakistan Wind Farm Cluster** | Pakistan              |          4 | Normalized actual power generation |                        8 | Jan. 2, 2017 – Dec. 31, 2021 | 1 hour     |

---

##  1. China Wind Farm Cluster Dataset

The China wind farm cluster dataset originates from a competition project organized as part of the **Digital China Innovation Contest**.

### Dataset Information

* **Number of wind farms:** 5
* **Power variable:** Actual electricity generation
* **Meteorological variables:** 10
* **Time period:** January 3, 2022 – April 30, 2023
* **Temporal resolution:** 15 minutes
* **Region:** Eastern coastal China

### Correlation of Daily Mean Power Generation

The Pearson correlation coefficients of the daily mean power generation among different wind farms are shown below.

🇨🇳 China Wind Farm Cluster


<img width="434" height="391" alt="image" src="https://github.com/user-attachments/assets/f055993c-a012-4383-9734-a16f82e307a6" />

The five wind farms in the China dataset exhibit relatively strong correlations in daily mean power generation, with pairwise correlation coefficients ranging from approximately 0.60 to 0.86.



### Variables Included in the Datasets
Dataset 1 — China Wind Farm Cluster
* Variable	Unit
* Power output	MW
* Pressure	Pa
* Relative humidity	%
* Cloud cover	—
* 10-m wind speed	m/s
* 10-m wind direction	°
* Temperature	K
* Radiation intensity	J/m²
* Rainfall	m
* 100-m wind speed	m/s
* 100-m wind direction	°

The China dataset contains 1 power variable and 10 meteorological variables.

### Original Source

🔗 [Digital China Innovation Contest](https://www.dcic-china.com/competitions/10098)

> The dataset contains synchronized wind power generation and meteorological observations for multiple wind farms, making it suitable for multi-site wind power forecasting and wind farm cluster forecasting studies.

---



##  2. Pakistan Wind Farm Cluster Dataset

The Pakistan wind farm cluster dataset originates from a corporate wind power forecasting project published on **Kaggle**.

### Dataset Information

* **Number of wind farms:** 4
* **Power variable:** Actual electricity generation
* **Meteorological variables:** 8
* **Time period:** January 2, 2017 – December 31, 2021
* **Temporal resolution:** 1 hour
* **Region:** Pakistan
* **Power preprocessing:** Power generation values were pre-normalized in the original dataset

### Pakistan Wind Farm Cluster

<img width="434" height="391" alt="image" src="https://github.com/user-attachments/assets/035e2045-642e-4e67-8b81-7a0a654869e5" />

The four wind farms in the Pakistan dataset show relatively weaker correlations, with pairwise correlation coefficients ranging from approximately 0.16 to 0.58.

### Dataset 2 — Pakistan Wind Farm Cluster
Variable	Unit
* Power	Normalized
* 2-m temperature	°F
* 2-m relative humidity	%
* 2-m dew point	°F
* 10-m wind speed	m/s
* 100-m wind speed	m/s
* 10-m wind direction	°
* 100-m wind direction	°
* 10-m wind gusts	m/s

The Pakistan dataset contains 1 power variable and 8 meteorological variables.

### Original Source

🔗 [Wind Power Generation Data Forecasting — Kaggle](https://www.kaggle.com/datasets/mubashirrahim/wind-power-generation-data-forecasting)

> The dataset provides long-term wind power generation records together with meteorological measurements from multiple wind farms. The original power generation data have already been normalized.



## 📌 Data  in this repository

The dataset used in this repository consists of data from various wind farms in two regions that have been consolidated and processed.

---

## 📧 Contact

If you have any questions regarding the dataset preprocessing or experimental settings, please feel free to open an **Issue** in this repository.
