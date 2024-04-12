# Market Segmentation on Electrical Vehicle Market of India

## By:

- Anubhav Sharma
- Jyotsna Kumari
- Kurapati Pavankumar
- Sanhita Saxena

## Project Description

This project explores the market dynamics and segmentation of the electric vehicle (EV) market in India. The objective is to analyze different segments of the market including two-wheelers, three-wheelers, and four-wheelers, and provide insights into the optimal target segments.


## Overview

The rapid growth of the EV market in India is driven by government initiatives, technological advancements, and increasing environmental awareness. This project aims to provide insights into different market segments within the Indian EV market and offers targeted marketing and development strategies for EV startups.


## Data Sources

- **EV Sales Dataset:** [Society of Manufacturers of Electric Vehicles](https://www.smev.in/statistics)
- **EV Usage in India:** [data.gov.in](https://data.gov.in/resource/category-wise-number-electric-vehicles-used-roads-india-03-august-2022)
- **Demographic Data:** [Google Sheets](https://docs.google.com/spreadsheets/d/1deb1cQsAMGCT_njTbpTaUUgUfOgtA/x8ggx61N77zQzs/edit#gid=1871162304)


## Methodology

Data was preprocessed using Pandas and various machine learning algorithms (e.g., K-Means, DBSCAN) were applied to extract different market segments. Each team member focused on a different aspect of the market (e.g., sentiment-based segmentation, market dynamics, and geographical segmentation) to gain comprehensive insights.

## Segment Overviews and Findings

### Market Dynamic-Based Segmentation of Electric Vehicle Market

- **Clustering Algorithms:** K-Means clustering was applied on sales data, age data, and EV models.
- **Target Segments:** The analysis focused on age, model, and price segments, highlighting the popularity of three-wheeler EVs and potential opportunities in higher-priced four-wheeler EVs.

### Sentiment-Based Segmentation: Four-Wheeler Segmentation

- **Data Source:** [CarWale](https://www.carwale.com/)
- **Clustering Algorithm:** K-Means clustering identified three segments:
    - Luxury-focused, high-performance EVs.
    - Balanced, performance and comfort-oriented EVs.
    - Basic, entry-level EVs for budget-conscious consumers.

### Sentiment-Based Segmentation: Two-Wheeler Segmentation

- **Data Source:** [BikeWale](https://www.bikewale.com/)
- **Clustering Algorithm:** K-Means clustering identified three segments similar to the four-wheeler analysis.
- **Target Segment:** The analysis suggests focusing on EVs with a balance between performance and comfort to cater to a wide range of customers.

### Geographical Segmentation of the Electric Vehicle Market

- **Data Sources:** Data on EV usage and charging stations in India were merged to create a comprehensive dataset.
- **Clustering Algorithm:** Various clustering methods (K-Means, DBSCAN, Hierarchical) identified three main clusters of market composition across India.
- **Target Segment:** Cluster 0, representing a balanced market, offers opportunities for introducing new EV types and establishing a foothold in states like Chhattisgarh and Tamil Nadu.

## Conclusion

This project provides comprehensive insights into the Indian EV market, offering potential areas of focus for startups and businesses to target and strategize their marketing and development efforts.
