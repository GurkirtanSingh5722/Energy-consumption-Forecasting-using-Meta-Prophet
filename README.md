# PJME Hourly Energy Consumption Forecasting using Meta Prophet

This project aims to forecast PJME daily aggregated from hourly energy consumption using the Meta Prophet model, a powerful and flexible tool for time series analysis that handles trends, seasonality, and holiday effects.

## 📁 Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Meta Prophet Model](#meta-prophet-model)
- [Installation](#installation)
- [Data Preprocessing](#data-preprocessing)
- [Forecasting Steps](#forecasting-steps)
- [Results](#results)
- [Conclusions](#conclusions)
- [References](#references)

## 📝 Project Overview

This project utilizes the Meta Prophet model to perform time series forecasting on the PJME hourly energy consumption dataset. The goal is to build a model that captures seasonal patterns and trends to predict future energy consumption effectively.

## 📊 Dataset

The dataset used for this project contains hourly energy consumption data (`PJME_MW`) from the PJM East region. It covers multiple years, providing a comprehensive view of hourly variations in electricity demand.

- **Source:** [PJME Hourly Energy Consumption Dataset](Available in the repository itself.) 
- **Columns:**
  - `Datetime`: Timestamp of the recorded data.
  - `PJME_MW`: Hourly energy consumption in Megawatts (MW).

## 📈 Meta Prophet Model

Meta Prophet is an open-source forecasting tool that is built specifically for time series data. It automatically identifies trends, seasonality, and holidays in data to create an accurate forecast. It is particularly useful for time series with daily observations over an extended period.

### Key Features of Meta Prophet:
- **Automatic Trend Detection:** Identifies linear and non-linear trends.
- **Seasonality Modeling:** Supports multiple seasonalities, such as daily, weekly, and yearly.
- **Holiday Effects:** Allows the inclusion of specific holidays or events that affect the time series data.

## 🛠️ Installation

To run this project, you will need to install the following Python packages:

```bash
pip install pandas matplotlib prophet
