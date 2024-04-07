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
The second sub-assignment for the Business Statistics master's course at the Amsterdam University of Applied Sciences focused on understanding the extent to which companies are aligning the technical aspects of their AI systems with the compliance requirements under the EU AI Act (AIA). This assignment extends the research initially conducted by Dey & Bhaumik (2023).

Key activities in this research included:

- Data Collection: Additional data was gathered through interviews with representatives from Shell and TAPP, companies that use AI in customer-related processes. These interviews were structured around a survey created by Dey & Bhaumik (2023), focusing on six AIA-related topics: Data & Model, Technical documentation, User application, Model monitoring, Risk Management, and AIA knowledge.
- Data Analysis: The analysis combined existing data from 21 companies with new data from 14 companies collected by students. Responses were categorized and analyzed based on AIA compliance, using a standardized scoring system to convert answers into a 0 to 1 range. This approach facilitated the calculation of actual compliance scores and feelings scores, allowing for the identification of any exaggeration in compliance levels reported by participants.

Key Insights and Results:

- An analysis across various topics revealed tendencies among companies to exaggerate their compliance in areas such as AIA knowledge and data & model management. Model monitoring showed the highest actual compliance scores, while risk management displayed the most significant variation in scores. A standout observation was a particular company (Company 15) that exhibited high exaggeration scores alongside the - lowest actual compliance, indicating a lack of preparedness for the AIA.
- The research also explored weighting different topics more heavily to assess their impact on the overall compliance picture. This analysis showed that giving more weight to certain topics like AIA knowledge or data & model management could shift the balance between actual compliance and perceived compliance, as reflected in exaggeration scores.

Conclusions:

The study concluded that while most companies tend to overstate their readiness for the AIA, particularly in areas of AIA knowledge and data & model management, there's a general trend towards reasonable compliance in model monitoring. The disparities in compliance and exaggeration scores across different domains suggest that companies may benefit from targeted efforts to enhance their understanding and implementation of AIA requirements, particularly in areas where they currently feel less prepared.
