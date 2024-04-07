# Business-statistics
## Sub-assignment 1:

This assignment is a data analysis performed in a Jupyter Notebook, focused on understanding the factors that influence the valuation of residential properties. Here's a summary of the steps taken:

1. Importing Packages and Data: Several Python libraries were imported for data analysis and visualization, including pandas, matplotlib, numpy, scipy, seaborn, folium, and more. The dataset Housing.csv was loaded for analysis.

2. Exploratory Data Analysis (EDA): Various visualizations were created to investigate the location and other aspects of the housing, including maps using Folium and a correlation heatmap with Seaborn. Missing values were also examined, and data was visualized in various ways, such as with scatter plots and bar charts.

3. Data Cleaning: Missing values for 'total_bedrooms' were filled with the average number of bedrooms per county. Additionally, rows with extreme values for house prices and the median age of houses were removed.

4. Categorical Subquestions:

- Research was conducted into the significance of differences between medians through visual inspection and statistical tests such as the Shapiro-Wilk test for normality, Bartlett and Levene's test for variance, and the Kruskal-Wallis test.
- Linear regression analyses were performed to investigate the relationship between various factors and median house value, examining different variables such as 'county', 'ocean_proximity', 'median_income', 'total_bedrooms', and 'housing_median_age'.
  
5. Multi-level Analysis: This involved using mixed linear models to explore how the valuation of homes is influenced by different levels of data, particularly at the county level. This included models with random intercepts and slopes for variables such as 'median_income', 'total_rooms', and 'housing_median_age'.

The assignment combines thorough data exploration with advanced statistical analyses to gain insights into the factors that influence home values. It utilizes both descriptive statistics and visualizations as well as inferential statistics to examine relationships between variables and test hypotheses.

## Sub-assignment 2: 
