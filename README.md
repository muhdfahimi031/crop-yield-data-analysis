# Crop Yield Data Analysis

A data analysis project examining how environmental and management factors affect agricultural yield across different crops and regions in Malaysia.

## Overview

This project analyzes a dataset of 180 crop trial records covering 5 crop types (Rice, Palm Oil, Durian, Banana, Corn) across 4 Malaysian regions (Pahang, Johor, Melaka, Selangor). The goal was to identify which factors — soil quality, rainfall, temperature, or fertilizer use — most strongly influence yield outcomes, and to practice core data analysis skills: cleaning, summarizing, correlating, and visualizing data.

**Note:** This dataset was synthetically generated for portfolio-building purposes. It does not represent real farm records.

## Dataset

| Column | Description |
|---|---|
| ID | Record identifier |
| Crop | Rice, Palm Oil, Durian, Banana, Corn |
| Region | Malaysia state (Pahang, Johor, Melaka, Selangor) |
| Soil Quality Index | Soil quality score (0–100 scale) |
| Rainfall mm | Rainfall in millimeters |
| Avg Temp C | Average temperature in Celsius |
| Fertilizer kg/ha | Fertilizer applied per hectare |
| Yield kg/ha | Crop yield per hectare (target variable) |

## Methodology

1. **Data preparation** — structured and cleaned in the `Raw Data` tab.
2. **Summary statistics** — average yield by crop type and by region, calculated with `AVERAGEIF`.
3. **Correlation analysis** — used `CORREL` to measure the relationship between yield and soil quality, fertilizer use, and rainfall.
4. **Visualization** — bar charts comparing crops and regions, and a scatter chart plotting soil quality against yield.

All calculations use live spreadsheet formulas (not hardcoded values), so the analysis updates automatically if the underlying data changes.

## Key Insights

- Yield varies meaningfully by crop type and by region — see the `Analysis` tab for exact averages.
- Soil quality shows a positive correlation with yield, consistent with agronomic principles from real crop trial work.
- Fertilizer application also correlates with yield, suggesting input management is a key lever alongside natural soil and climate conditions.
- Regional breakdown highlights which areas produce above-average yields — useful for resource allocation decisions.

## Tools Used

- **Excel** — data structuring, `AVERAGEIF` and `CORREL` formulas, pivot-style summary tables, bar and scatter charts

## Files

- `Crop_Yield_Analysis_Portfolio.xlsx` — full workbook with Raw Data, Analysis, Charts, and Summary tabs

## About Me

Agrotechnology graduate (UiTM Melaka) transitioning into data analysis, drawing on hands-on experience analyzing agricultural trial data during my internship at Top Fruits Sdn. Bhd.
