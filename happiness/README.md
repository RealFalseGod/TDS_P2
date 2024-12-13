# Data Analysis Report

The data analysis of the ‘happiness.csv’ dataset reveals various trends, correlations, and patterns related to happiness across different countries and decades, hinting at the influence of socio-economic factors on well-being. The following narrative summarizes the insights drawn from the dataset.

### Overview of the Dataset
The dataset contains several pivotal variables related to happiness metrics for 165 unique countries over a period from 2005 to 2023, with a total of 2363 entries. The data points include subjective happiness ratings (Life Ladder), economic indicators (Log GDP per capita), health metrics (Healthy life expectancy at birth), social constructs (Social support and Freedom to make life choices), and personal sentiments (Perceptions of corruption, Positive affect, and Negative affect).

### Yearly Trends
The dataset indicates an average year of approximately 2015, with a notable range from 2005 to 2023. The rising number of recorded happiness data across the years suggests increased global interest in measuring subjective well-being.

### Happiness Indicators: Key Findings
1. **Life Ladder:** The average Life Ladder score across the dataset is approximately 5.48, with a standard deviation of about 1.13, indicating diversity in happiness perceptions. The minimum score of 1.281 signifies that some countries report extremely low happiness levels, while the maximum score is 8.019, showing that certain nations are much happier.

2. **Log GDP per capita:** This economic indicator, with an average score of approximately 9.40 and a range from 5.527 to 11.676, displays a strong correlation (0.78) with the Life Ladder scores. This suggests that higher GDP per capita is strongly associated with increased happiness.

3. **Social Support and Freedom:** Both social support (mean = 0.81) and freedom to make life choices (mean = 0.75) reveal a significant relationship with happiness scores, with correlation coefficients of approximately 0.72 and 0.54 respectively. Countries with strong social networks and personal freedom tend to report higher happiness levels.

### Health Metrics
Healthy life expectancy at birth shows a mean value of 63.4 years. This variable correlates positively with the Life Ladder at 0.72, signifying that better health outcomes contribute significantly to citizens’ reported happiness levels.

### Analyzing Negative and Positive Affect
The average positive affect stands at around 0.65, while the negative affect averages a lower score of approximately 0.27. Notably, these two sentiments have a moderate negative correlation (-0.33), indicating that an increase in positive feelings contributes to a reduction in negative sentiments. 

### Correlation and Outlier Analysis
- **Corruption Perception:** There is a noteworthy negative correlation (-0.43) between perceptions of corruption and the Life Ladder, suggesting that countries with lower corruption perceptions tend to produce happier outcomes. Countries like Denmark or New Zealand might surface as examples of this trend.

- **Outlier Detection:** Countries with exceptionally low Life Ladder scores, for instance, fail to align with other socio-economic measures, indicating potential anomalies due to ongoing conflicts, systemic governmental issues, or severe poverty where happiness levels are starkly low compared to their GDP. Countries like Afghanistan or some nations in sub-Saharan Africa could be illustrative cases where high challenges related to socio-economic systems correlate with low happiness metrics.

### Missing Values
The analysis revealed varying degrees of missing data across several key variables. For instance, the metrics on "Log GDP per capita" and "Healthy life expectancy at birth" have missing entries of 28 and 63, respectively. The presence of missing data in important fields like Generosity, Perceptions of corruption, and others could skew certain interpretations and necessitate careful handling during further analysis phases.

### Final Thoughts
The analysis of the ‘happiness.csv’ dataset indicates that GDP, health, social support, and personal freedom are critical drivers of happiness across countries. Additionally, as countries develop economically and socially, they could be expected to exhibit improvements in happiness levels. It would be beneficial for policymakers to focus on healthcare access, social infrastructure, and enhancing individual freedoms to boost overall life satisfaction among their populations. Further investigation into countries exhibiting anomalously low happiness scores despite favorable economic indicators could provide deeper insights and highlight potential areas for intervention.

## Visualizations

![correlation_heatmap.png](correlation_heatmap.png)
![Freedom to make life choices_distribution.png](Freedom to make life choices_distribution.png)
![Generosity_distribution.png](Generosity_distribution.png)
![Healthy life expectancy at birth_distribution.png](Healthy life expectancy at birth_distribution.png)
![Life Ladder_distribution.png](Life Ladder_distribution.png)
![Log GDP per capita_distribution.png](Log GDP per capita_distribution.png)
![Negative affect_distribution.png](Negative affect_distribution.png)
![Perceptions of corruption_distribution.png](Perceptions of corruption_distribution.png)
![Positive affect_distribution.png](Positive affect_distribution.png)
![Social support_distribution.png](Social support_distribution.png)
![year_distribution.png](year_distribution.png)