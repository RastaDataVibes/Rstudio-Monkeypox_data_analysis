# 🦠 Monkeypox Daily Epidemiology Analysis

[![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)](https://www.r-project.org/) 
[![R Markdown](https://img.shields.io/badge/R%20Markdown-2D8CFF?style=flat&logo=rmarkdown&logoColor=white)](https://rmarkdown.rstudio.com/)

## Overview
This project analyzes daily confirmed **monkeypox cases** using publicly available epidemiological data. The objective is to explore trends over time, visualize epidemic curves, and examine patterns by country, gender, hospitalization, and travel history.

## Dataset
- **Source:** Publicly available monkeypox epidemiological CSV data  
- **Key Variables:**  
  - `Date_confirmation` – date the case was confirmed  
  - Location: City, Country  
  - Demographics: Age, Gender  
  - Health status: Symptoms, Hospitalization, Isolation  
  - Travel history and outcome  

## Analysis & Visualizations
- **Data Cleaning:** Removed duplicates and missing confirmation dates, standardized date formats.  
- **Daily Case Counts:** Plotted epidemic curves and computed 7-day moving averages.  
- **Summary Tables:**  
  - Top affected countries  
  - Gender distribution  
  - Hospitalization and travel history  
- **Plots:** Line plots, bar charts, and moving averages to illustrate trends.

## 🎥 monkeypox_data_analysis walkthrough

To view the Rmd demo:

- [screenRecording.mov](screenRecording.mov)

⚠️ GitHub may not preview the file in-browser.  
Click **"View raw"** to download and play it locally.

## How to Use
1. Clone this repository:  
   ```bash
   git clone https://github.com/RastaDataVibes/Rstudio-Monkeypox_data_analysis.git

