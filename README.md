# Customer Segmentation for Tiered Pricing

## Overview
This project aims to perform customer segmentation analysis to support tiered pricing strategies. Using k-means clustering, we analyze synthetic customer data to identify distinct customer groups, providing insights into optimal pricing tiers tailored to each segment. This approach enhances revenue potential by aligning price points with customer willingness to pay.

## Data
- **Synthetic data** is generated to simulate customer behaviors across features:
  - `spending`: Monthly spending in USD
  - `business_size`: Business size (1 = Small, 2 = Medium, 3 = Large)
  - `usage_frequency`: Interaction frequency per month
  - `satisfaction_score`: Satisfaction rating (1–5)

## Methodology
1. **Data Generation**: Creates synthetic data simulating customer behaviors and spending.
2. **Preprocessing**: Standardizes data to improve clustering accuracy.
3. **Optimal Clustering**: Uses the Elbow Method to determine the best number of clusters.
4. **K-Means Clustering**: Segments customers into groups based on similar behaviors and spending patterns.
5. **Visualization**: Provides 2D plots of clusters for visual analysis.
6. **Cluster Profiling**: Summarizes each segment’s characteristics to aid in tiered pricing decisions.
7. **Pricing Recommendations**: Suggests tiered pricing for each segment based on cluster insights.

## Key Files
- `customer_segmentation.Rmd`: Main analysis file with code for data generation, processing, clustering, and visualization.
- `README.md`: Project overview and instructions.
- `requirements.txt`: List of packages used in the R Markdown analysis.

## Getting Started
To run the analysis:
1. Clone the repository.
2. Open `customer_segmentation.Rmd` in RStudio.
3. Install required packages by running:
   ```r
   install.packages(c("dplyr", "ggplot2", "cluster", "factoextra"))
   ```
4. Execute the R Markdown file to generate the analysis report.

## Results
The project outputs customer segments, visualized clusters, and pricing recommendations tailored to each segment. The findings can be applied in business contexts to create strategic, data-driven pricing tiers.
