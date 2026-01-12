# Melbourne Housing Market – Exploratory Data Analysis

## Overview
This project presents an exploratory data analysis (EDA) of the Melbourne housing market dataset, focusing on understanding how property prices relate to location, land size, and structural characteristics.

The analysis prioritizes clarity and interpretability, aiming to extract meaningful insights rather than building predictive models or dashboards.

---

## Dataset
- Source: Kaggle – Melbourne Housing Dataset
- Scope: Residential property sales in Melbourne
- Key variables:
  - Price
  - Region and Suburb
  - Land size
  - Number of rooms, bedrooms, and bathrooms
  - Geographic coordinates (latitude and longitude)

The dataset is relatively clean, allowing the analysis to focus on exploration rather than extensive preprocessing.

---

## Analysis Highlights

### Price Distribution
- Strong price concentration with significant right-skew.
- Median prices provide more reliable insights than averages due to outliers.

### Regional Analysis
- Property prices vary substantially across regions.
- Inner and coastal regions concentrate higher price tiers.
- Some regions exhibit non-linear relationships between land size and price.

### Land Size vs Price
- Larger land size does not necessarily imply higher prices.
- In several regions, very large lots are associated with lower median prices, suggesting location effects dominate size.

### Suburb-Level Insights
- Suburb analysis was used selectively to explain regional anomalies.
- Drilldowns confirmed that price variations are driven by micro-location rather than land size alone.

### Geospatial Visualization
- Interactive maps reveal clear spatial clustering of price tiers.
- Location proves to be the strongest determinant of property value.
- Price bins improve interpretability over continuous price scales for categorical analysis.

---

## Tools and Libraries
- Python 3.13
- pandas
- numpy
- plotly

All dependencies are listed in `requirements.txt`.

---


## Notes
This project focuses on exploratory analysis and insight generation.  
Dashboards and predictive modeling were intentionally left out to keep the scope concise and analytical.

---

## Next Steps (Optional)
- Consolidate multiple analyses into an interactive dashboard
- Extend the analysis with time-based trends
- Explore predictive modeling using selected features