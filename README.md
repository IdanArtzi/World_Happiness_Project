## World Happiness Analysis 
# Project Overview
This project analyzes the key factors influencing happiness across countries and regions using the World Happiness Report (2016) dataset. The goal was to identify economic, social, and institutional drivers of happiness through exploratory data analysis and visualization.
Generative AI (ChatGPT) was used to assist in generating Python code for data analysis and visualization, allowing faster iteration while maintaining full control over logic, validation, and interpretation.

## Dataset 📊
- Source: World Happiness Report 2016 (Kaggle)
- URL: https://www.kaggle.com/datasets/unsdsn/world-happiness?resource=download&select=2016.csv

## Technologies used 🛠 
- Python
- Jupyter Notebook
- Pandas, Matplotlib, Seaborn, Plotly, Dash
- ChatGPT (GenAI assistance)

## Dashboard 
link to the interactive dashboard:
file:///Users/user/Desktop/IBM%20Data%20Analytics%20/Happiness%20Dashboard.html

## Executive Summary
The following visualizations help understand the patterns and attributes that incluence global happiness.

### Correlation Heatmap
The Three main attributes that are correlated with higher happiness scores:
- economic prosperity
- strong family relationships
- longer healthy life expectancy
![Correlation Heatmap](images/gen_ai_heatmap.png)

### GDP per Capita vs Happiness
This scatter plot comparing GDP per capita and happiness across regions shows a strong upward trend:

- **There are several factors that effect happiness; economic, cultural, social, geographical and govermental**
- **Overall Trend** - Wealthier countries tend to report greater life satisfaction. 
- **Cultural Happiness?** - Several countries from Latin America have a higher happiness scores than their GDP would suggest (Costa Rica, Puerto Rico, Brazil, Aregentina and Panama).
- **Money isn't everything!** - The countries with the highest GDP per Capita, are not the happiest countries (Qatar, Kuwait, Luxembourg and Singapure).
- **The West vs The Rest?** edit!! - does the western societies score higher than the Rest of the world, outliers? such as east asia, and Israel? 
- On the other side of the trend, we can see that the majority of countries at the bottom of the happiness score and low GDP are from Sub-Saharan region, showing a geographical disadvantage that has a negative effect both on economic and happiness scores in this region.
![GDP vs Happiness](images/gen_ai_scatter.png)

### Happiness by Region
The pie chart reveals regional disparities, with certain regions contributing disproportionately to higher happiness scores. 
Such as North America and Australia & New Zealand. 
![Happiness by Region](images/gen_ai_pie.png)

### Global Happiness Map
Finally, the global map visually connects economic strength and public health outcomes. 
Countries with high GDP per capita also display higher healthy life expectancy in the tooltip data, reflecting the intertwined nature of economic and social development.
![Global Happiness](images/gen_ai_choropleth.png)
