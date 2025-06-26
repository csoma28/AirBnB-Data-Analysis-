
# Airbnb NYC Exploratory Data Analysis (EDA)

## Overview

This project presents a structured exploratory data analysis (EDA) of Airbnb listings in New York City. Using publicly available data, we explore listing characteristics, pricing patterns, host behavior, and guest engagement metrics. All conclusions are based strictly on observed data.

---

## Dataset Summary

- **Source:** Airbnb NYC public dataset
- **Total Listings:** 20,736
- **Fields:** Neighborhood, location, price, availability, ratings, reviews, licensing, bedrooms, beds, baths, etc.

---

## Project Objectives

- Explore the spatial and categorical distribution of listings  
- Analyze pricing and availability trends  
- Examine guest engagement through reviews and ratings  
- Investigate host behavior, including multi-listing patterns  
- Derive insights for hosts, analysts, and platform policy makers  

---

## EDA Workflow

### Data Cleaning
- Standardized column formats and types  
- Treated missing values and invalid entries  
- Filtered out extreme outliers in `price` and `availability`  

### Univariate & Bivariate Analysis
- Distribution analysis of `price`, `availability`, and `rating`  
- Relationship between `price` and `room_type`, `borough`, and `host activity`  

### Correlation & Geospatial Mapping
- Correlation heatmap for numerical features  
- Visualization of listing density and pricing across NYC  

---

## Key Insights (Based on Data)

### Pricing
- **Median Price:** $125  
- 75% of listings priced under $199  
- Listings above $500 are rare and skew the mean upward  

### Room Types
- Most common type: Entire home/apartment  
- Private rooms are more frequent outside Manhattan  

### Availability
- **Median availability:** 215 days/year  
- About 25% of listings have very low availability (< 87 days/year)  
- Listings with 365 days availability likely reflect professional hosts  

### Ratings & Reviews
- Majority of listings have ratings between 4.6 and 5.0  
- Higher review frequency correlates with availability and moderate pricing  

### Host Behavior
- **Median listings per host:** 2  
- Small number of hosts have over 100 listings  
- Many listings lack licensing information  

---

## Recommendations

### For Hosts
- Price competitively in the $100–$150 range for more consistent reviews  
- Increase availability beyond 200 days to improve visibility and bookings  
- Ensure complete and transparent listings (beds, baths, license info)  

### For Airbnb
- Monitor hosts managing >50 listings as potential commercial operators  
- Encourage license transparency across the platform  
- Consider mechanisms to control extreme pricing outliers  

---

## Technologies Used

- Python 3.10+  
- pandas, numpy, seaborn, matplotlib  
- Jupyter Notebook environment  

---

## Running the Project

1. Clone the repository or download the notebook  
2. Install dependencies:
```bash
pip install pandas numpy seaborn matplotlib
```
3. Run the notebook:
```bash
jupyter notebook Airbnb\ NY\ EDA.ipynb
```

---

## Project Files

```
├── Airbnb NY EDA.ipynb     # Main notebook
├── datasets.csv            # Airbnb NYC dataset
└── README.md               # Project documentation
```

---

## License

This project is open for educational use. Data is publicly sourced and intended for analysis and learning purposes.
