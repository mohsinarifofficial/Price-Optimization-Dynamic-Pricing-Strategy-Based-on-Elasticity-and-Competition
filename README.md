# Price-Optimization-Dynamic-Pricing-Strategy-Based-on-Elasticity-and-Competition
This project analyzes historical pricing and sales data to develop a data-driven price optimization strategy. Using pricing elasticity, competition benchmarking, and revenue simulation, it proposes dynamic pricing rules that increase sales revenue without compromising volume.



 Key Highlights
 Data Preparation & Cleaning
Parsed and explored competition dataset from Statso

Removed missing values and standardized date formats

Created bins for price brackets to group and analyze performance

 Exploratory Data Analysis
Visualized:

Price distributions of Your Store vs Competitor

Sales amount correlation with price and competitor price

Weekly trends in pricing for both stores

Compared total sales and competitive sales estimates

Elasticity Analysis
Computed price elasticity of demand:

% change in quantity sold relative to % change in price

Segmented items into Low, Medium, and High price categories

Measured average elasticity per segment

Dynamic Pricing Simulation
Applied rules:

Raise prices by 5% for medium-segment products (more inelastic)

Reduce prices by 10% for high-segment products (more elastic)

Calculated expected new sales using dynamic prices

Compared existing vs. dynamic total revenue

