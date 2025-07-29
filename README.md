# KSI-VRU-VisionZero-Toronto

Interrupted Time Series analysis of Killed or Seriously Injured (KSI) collisions among Vulnerable Road Users (VRUs) in Toronto, before and after the implementation of Vision Zero in 2017.

## 📊 Objective

This project evaluates trends in KSI events involving pedestrians, cyclists, and motorcyclists between 2010 and 2024. We estimate whether Vision Zero policies had a measurable impact.

## 🧪 Methods

- Data filtering and wrangling using `dplyr`, `tidyverse`
- Trend plotting using `ggplot2`
- Interrupted Time Series (ITS) regression models
- Stratified models by injury severity and VRU type

## 📁 Structure

- `analysis/KSI_analysis.Rmd`: Main RMarkdown file with code and commentary.
- `analysis/KSI_analysis.html`: Rendered output of the RMarkdown.
- `data/Police_KSI.xlsx`: **Not shared** publicly due to privacy.
- `figures/`: Optional directory for storing exported charts.

## 🔒 Privacy Note

The collision data used in this project includes KSI (Killed or Seriously Injured) information originally provided by the Toronto Police Service. The dataset used here was obtained through the **City of Toronto**, and is approved and verified by city staff.  
**Due to the sensitive nature of the data, the full dataset is not shared publicly.**

## 📦 R Packages Used

- tidyverse
- ggplot2
- readxl / writexl / openxlsx
- broom
- purrr

## 📆 Time Frame

- Data: 2010–2024
- Vision Zero start year: **2017** (dashed vertical line on plots)

## 📜 License

MIT License
