## Customer Segmentation Analysis Project

## Project Overview

This project performs advanced customer segmentation analysis on retail transaction data using RFM (Recency, Frequency, Monetary) metrics and K-means clustering in Tableau. By identifying distinct customer groups, this analysis enables targeted marketing strategies, personalized communication, and improved customer relationship management.

The analysis uses the "Online Retail" dataset, containing transactions from a UK-based online retailer between 2010-2011, to identify five customer segments with unique behavioral patterns and business value.
https://www.kaggle.com/datasets/vijayuv/onlineretail

## Key Findings

Through this analysis, we identified five distinct customer segments:

1. **High-Value Loyalists (22%)**: Frequent shoppers with high monetary value who purchased within the last 15-45 days
2. **Recent High-Spenders (18%)**: Recent customers with high-value purchases but lower frequency
3. **Consistent Mid-Tier (27%)**: Regular shoppers with moderate spending and 30-90 day recency
4. **At-Risk High-Value (15%)**: Previously valuable customers who haven't purchased in 90-200 days
5. **Low-Value Occasional (18%)**: Infrequent shoppers with low monetary value and 60-200 day recency

Each segment requires different marketing approaches to maximize customer lifetime value.

## Data Exploration

The initial data exploration revealed several key insights:

- Dataset contains 541,909 transactions from 4,373 unique customers
- Time period: December 2010 to December 2011
- 25% of customer IDs were missing, requiring data cleaning
- Approximately 2% of transactions had negative quantities (cancelled orders)
- Strong positive correlation (0.68) between frequency and monetary value
- Highly skewed monetary distribution with a few extremely high-value customers
- Seasonal purchasing patterns with peaks in November-December

The RFM analysis revealed significant variations in customer behavior:
- Recency: 1-373 days
- Frequency: 1-250 purchases
- Monetary: £3-£280,000

## Project Structure
```
customer_segmentation_analysis/
├── data/                    # Raw and processed data files
├── notebooks/               # Jupyter notebooks for data preprocessing
├── tableau_workbooks/       # Tableau workbooks
├── visualizations/          # Exported visualizations and screenshots
├── process_documentation/   # Detailed documentation of each step
└── docs/                    # Project documentation and recommendations
```

## Skills & Technologies Used

### Data Processing & Analysis
- **Python**: Data preprocessing and feature engineering
- **Pandas/NumPy**: Data manipulation and statistical analysis
- **Matplotlib/Seaborn**: Data visualization and exploratory analysis
- **Jupyter Notebooks**: Interactive development and documentation

### Data Visualization & Segmentation
- **Tableau**: Primary tool for clustering and visualization
- **K-means Clustering**: Segmentation algorithm
- **RFM Analysis**: Customer value measurement framework

### Project Management & Documentation
- **Git/GitHub**: Version control and project management
- **Markdown**: Documentation format
- **Process Documentation**: Methodical recording of all analysis steps

## Business Applications

This customer segmentation model enables businesses to:

1. **Optimize Marketing Budget**: Allocate resources to the most valuable customer segments
2. **Personalize Communication**: Tailor messaging based on segment characteristics
3. **Improve Retention**: Identify at-risk customers before they churn
4. **Enhance Customer Experience**: Provide segment-specific service levels
5. **Boost Revenue**: Target cross-selling and upselling strategies to appropriate segments

## Recommended Marketing Strategies

Based on the segmentation, we recommend:

- **High-Value Loyalists**: Loyalty programs, premium services, early access to new products
- **Recent High-Spenders**: Engagement campaigns, loyalty program enrollment, complementary product recommendations
- **Consistent Mid-Tier**: Regular engagement, mid-tier promotions, incentives to increase order value
- **At-Risk High-Value**: Re-engagement campaigns, special offers, feedback surveys
- **Low-Value Occasional**: Low-cost engagement, special promotions to increase purchase frequency
