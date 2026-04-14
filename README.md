# Amazon-Pricing-Strategy-Customer-Satisfaction-Analysis

__This project was created by Rizky Nanda Praditia__

Dashboard link : https://public.tableau.com/shared/HFQ27XFSQ?:display_count=n&:origin=viz_share_link

__Repository Outline__

- README.md - Overview of the project
- amazon.csv - Dataset used in this analysis
- amazon-sales-analysis.ipynb - Python notebook containing Data Cleaning, Exploratory Data Analysis, and inferential statistical tests.

__Project Overview__

In the competitive e-commerce landscape, pricing strategies and discounts are primary drivers of consumer traffic. However, aggressive discounting can often lead to a perceived reduction in product quality. This project performs an end-to-end data analysis on Amazon product data to decode the relationship between pricing dynamics, discount depths, and customer satisfaction (ratings).

__Project Objectives__

- Evaluate Pricing Efficiency: Analyze the impact of discount depths on product traction.
- Assess Satisfaction Drivers: Identify whether affordability (discounts) or product quality (ratings) is the dominant factor in consumer engagement.
- Statistical Validation: Use Hypothesis Testing to scientifically determine if high-discount products significantly differ in quality/satisfaction compared to low-discount products.
- Actionable Recommendations: Provide data-backed insights for e-commerce sellers to optimize their pricing without damaging brand reputation.

__Tech Stack & Libraries__

- Language: Python 3.x
- Data Manipulation: Pandas, NumPy
- Visualization: Matplotlib, Seaborn
- Statistics: SciPy (T-Testing, Descriptive Stats)
- Environment: Jupyter Notebook / Google Colab

__Dataset Description__

The analysis utilizes the amazon.csv dataset, which includes:

- Product Metadata: Name, Category, Product ID.
- Pricing Data: Actual Price, Discounted Price, Discount Percentage.
- Customer Feedback: Rating, Rating Count (Review volume).
- Contextual Data: Product descriptions and review content.

__Key Analysis Steps__

- Data Cleaning: Currency conversion, handling missing values, and data type optimization (converting strings to numeric floats).
- Exploratory Data Analysis (EDA): Visualizing category distributions and price-vs-rating correlations.
- Descriptive Statistics: Analyzing central tendencies and identifying outliers in review volumes.
- Inferential Statistics: Conducting a Two-Sample Independent T-Test to compare ratings between high-discount (>50%) and low-discount (≤50%) product groups.

__Key Insights__

- Category Dominance: Electronics and Accessories represent the largest share of the marketplace.
- The Discount Paradox: Visual analysis indicates that high discounts do not linearly correlate with higher ratings, suggesting customers value quality over price alone.
- Social Proof: A small percentage of "Superstar" products drive the majority of user engagement (rating counts).

__Conclusion & Recommendations__

The study concludes that while discounts drive volume, they do not statistically guarantee higher satisfaction. Sellers are advised to maintain a "Quality-First" approach, as data shows that moderate discounts (20-40%) coupled with high product reliability yield the best long-term ratings.
