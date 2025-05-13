# COMP2501 Introduction to Data Science and Engineering

## Predictive Modelling for Enhanced Police Response: Forecasting Monthly Accident Rates Using Transport, Economic, and Weather Data

---

## Project Strucutre

```bash
├── csv
│   ├── accidents_by_month_data.csv
│   ├── cpi_data_monthly.csv
│   ├── daily_HKO_RF_ALL.csv
│   ├── hko_rf_monthly.csv
│   ├── hsi_index_data.csv
│   ├── traffic_data_monthly.csv
├── .gitignore
├── requirements.txt # Python dependencies
├── Rplots.pdf # Plot of the model
├── summary.pdf # Summary of the project
├── summary.md # Summary of the project produced in R analysis
├── README.md
├── analysis.R # R script for running the model
└── rf_convert.py # Python script for converting daily rainfall data to monthly
```

## Instructions to running the model

First install python dependencies by running:

`pip3 install -r requirements.txt`

Then if necessary to update and calculate the data of monthly rainfall of Hong Kong, run:

`python3 rf_convert.py`

To run the R model, run:

`Rscript analysis.R`
