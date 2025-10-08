# Seattle Weather Project

> Analyze and compare precipitation between Seattle and New York.
---

## Project Overview

This project explores precipitation trends in Seattle, WA and New York City, NY to understand seasonal rainfall difference.

- **Objective:** Compare and visualize rainfall difference between Seattle, WA and New York, NY using Python.
- **Domain:** Climate Analytics
- **Key Techniques:** Data Inspection, Data Manipulation, Data Cleaning, Tidy, Matplotlib, Seaborn, Data Visualization

---

## Project Structure

```
├── data/                 # Raw and processed data
├── code/                 # Jupyter notebooks and Python scripts
├── reports/              # Generated reports and visualizations
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## Data

- **Source:** National Centers for Enviornmental Information: (https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND)
- **Description:** STATION, NAME, DATE, DAPR, MDPR, PRCP, SNOW, SNWD, WESD, WESF
- **License:**

---

## Analysis

Analysis was conducted in Python using Jupyter Notebook.

Main Analysis Methods:
1. Open code/Weather_Data.ipynb
2. Run all cells in order
    - Load and inspect data set
    - Convert data types of columns of the data frames to the correct type
    - Clean Data (Removing unnecessary parts)
    - Impute missing data (NaN values)
    - Join the Seattle and New York City data frames [Date], [Precipitation]
    - Ensure using tidy
    - Rename columns
    - Create data visualizations

---

## Results

According to the comparison of montly proportion of days of precipitatin between Seattle and New York City, Seattle has more rainfall compared to New York City.

---

## Authors

- Jimmy Nam - [@Jimmynam0103](https://github.com/Jimmynam0103/Weather/tree/main)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Tools/libraries: Python, Pandas, Numpy, Matplotlib, Seaborn
- Data Source: NOAA Climate data Online
- Inspiration: Climate Analysis
# Weather
