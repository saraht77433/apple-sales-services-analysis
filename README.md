# Understanding the Relationship Between Apple Product Sales and Services Revenue

## Project Overview
This project analyzes regional Apple product sales and their relationship to Services revenue across U.S. states and global markets. By examining unit sales data for iPhone, iPad, Mac, and Wearables alongside Services revenue, this project aims to identify geographic areas where product sales most strongly correlate with service income. These insights can help Apple tailor marketing, product bundles, and subscription offerings to specific regions for better business outcomes.

## Motivation
Apple’s product lines perform differently across regions. Understanding how product sales relate to Services revenue can inform smarter business strategies, targeting investments and promotions where they will have the most impact.

## Data Description
The dataset is a CSV file containing Apple’s unit sales by product category and Services revenue, broken down by U.S. states and global regions. The data includes:
- Product unit sales: iPhone, iPad, Mac, Wearables (in millions)
- Services revenue (in billions)
- Geographic labels: State and Region

## Project Workflow
1. **Exploratory Data Analysis (EDA):**  
   - Used descriptive statistics and visualizations to understand sales distribution by region.  
   - Identified key markets with strong sales, such as California, New York, Florida, and Texas.

2. **Data Preparation and Feature Engineering:**  
   - Standardized numeric features using StandardScaler.  
   - Created additional features like Total Product Sales and iPhone Ratio for exploratory purposes.

3. **Modeling and Evaluation:**  
   - Built a linear regression model to predict Services revenue based on product sales.  
   - Found that Wearables and Mac sales had the strongest positive association with Services revenue.  
   - Observed a slightly negative coefficient for iPhone sales, suggesting complex regional dynamics.

## Key Findings
- iPhones dominate unit sales but do not strongly predict Services revenue in this dataset.  
- Wearables and Mac sales show a stronger relationship with Services revenue.  
- Regional differences highlight the need for tailored marketing and bundling strategies.

## Limitations
- Dataset lacks pricing, customer engagement, and temporal detail, limiting model performance.  
- Linear regression showed low predictive accuracy; advanced models may yield better insights.  
- Snapshot data does not capture changing trends over time.

## Future Work
- Incorporate additional data such as App Store usage and subscription history.  
- Explore time series analysis for dynamic trend detection.  
- Test more complex models like decision trees or random forests.

## Deliverables
- This README document detailing the project overview, methodology, and findings.  
- Jupyter Notebook with all code used for data analysis, modeling, and visualization.

## How to Use This Repository
- Open the Jupyter Notebook to run the data analysis and modeling step-by-step.  
- Review visualizations and code comments for insight into each step.

---

