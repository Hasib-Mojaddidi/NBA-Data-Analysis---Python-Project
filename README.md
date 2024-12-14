# NBA-Data-Analysis---Python-Project
Data-Driven Insights into NBA Player Performance: Trends, Correlations, and Predictive Modeling
NBA Player Performance Analysis
🏀 Overview
This project focuses on analyzing NBA player performance metrics using data-driven techniques. The dataset includes key performance statistics such as points, rebounds, assists, minutes played, and shooting percentages, among others. By leveraging statistical analysis, clustering, and visualization techniques, the project provides meaningful insights into player roles, performance trends, and scoring patterns.

📊 Objectives
Explore and clean the NBA dataset to ensure quality and consistency.
Perform descriptive statistics and correlation analysis to identify relationships between performance metrics.
Categorize players into scoring categories and analyze performance by player position.
Implement clustering to identify natural groupings of players based on key performance indicators.
Visualize insights with heatmaps, scatter plots, and clustering graphs.
📁 Dataset
The dataset includes the following variables:

Player: Name of the player.
Position: Player's on-court position (e.g., Guard, Forward, Center).
Minutes: Average minutes played per game.
Field Goal Percentage: Accuracy of field goal attempts.
Three-Point Percentage: Accuracy of three-point attempts.
Free Throw Percentage: Accuracy of free throw attempts.
Rebounds: Average number of rebounds per game.
Assists: Average number of assists per game.
Steals: Average number of steals per game.
Blocks: Average number of blocks per game.
Points: Average points scored per game.
Team: Player's team.
Conference: Player's conference (East/West).
Scorer Category: Categorization of players into scoring tiers (e.g., Low, Medium, High Scorer).
🔍 Key Features
Exploratory Data Analysis (EDA):

Visualized the correlation between performance metrics using heatmaps.
Identified key trends and outliers in player statistics.
Categorical Analysis:

Analyzed player performance by positions and scoring categories.
Summarized the distribution of players in each scoring tier.
Clustering Analysis:

Implemented K-Means clustering to identify player groupings based on metrics like points, assists, rebounds, and minutes played.
Visualized clusters using PCA (Principal Component Analysis) to simplify the high-dimensional space.
Statistical Insights:

Conducted correlation analysis to understand relationships between variables (e.g., minutes played and points scored).
Explored feature importance to assess which variables most strongly influence performance.
📈 Key Findings
Scoring Analysis:
High scorers tend to have more minutes on the court and higher shooting percentages.
Guards dominate assists, while Centers excel in rebounds and blocks.
Correlation Insights:
Points are positively correlated with minutes, assists, and rebounds.
Shooting percentages (field goals, three-pointers, free throws) show moderate correlations with overall scoring.
Clustering:
Players were grouped into three clusters based on performance metrics:
Elite Performers: High-scoring players with significant playing time.
Role Players: Players contributing moderately across key metrics.
Bench Players: Limited scoring and minutes, often in supporting roles.
🛠️ Tools & Technologies
Programming Language: Python
Libraries:
Pandas: Data manipulation and preprocessing.
Matplotlib & Seaborn: Data visualization.
Scikit-learn: Machine learning for clustering and PCA.
Jupyter Notebook: Development environment.
