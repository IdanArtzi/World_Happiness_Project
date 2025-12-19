## World Happiness Analysis – GenAI-Assisted EDA
# Project Overview
This project analyzes the key factors influencing happiness across countries and regions using the World Happiness Report (2016) dataset. The goal was to identify economic, social, and institutional drivers of happiness through exploratory data analysis and visualization.
Generative AI (ChatGPT) was used to assist in generating Python code for data analysis and visualization, allowing faster iteration while maintaining full control over logic, validation, and interpretation.

## Dataset 📊
- Source: World Happiness Report 2016 (Kaggle)
- URL: https://www.kaggle.com/datasets/unsdsn/world-happiness?resource=download&select=2016.csv
- Format: Clean CSV file
- Preprocessing: No data cleaning required

## Technologies used 🛠 
- Python
- Jupyter Notebook
- Pandas, Matplotlib, Seaborn, Plotly, Dash
- ChatGPT (GenAI assistance)

## Dashboard 
link to the dashboard:
file:///Users/user/Desktop/IBM%20Data%20Analytics%20/Happiness%20Dashboard.html

## Exploratory Data Analysis
In this project I wanted to find the main factors that influences happiness around the world. 
by compering different attributes and visualizng them I was able to find positive and negative patterns in the dataset.


### Correlation Heatmap
The correlation heatmap indicates that economic prosperity, strong family relationships, and longer healthy life expectancy are consistently associated with higher happiness scores.
![Correlation Heatmap](images/gen_ai_heatmap.png)

### GDP per Capita vs Happiness
This scatter plot comparing GDP per capita and happiness across regions shows a strong upward trend: 
Wealthier regions tend to report greater life satisfaction. 
However, several countries stand out by achieving higher happiness levels than their GDP alone would predict—suggesting cultural, social, or governance-driven effects.
![GDP vs Happiness](images/gen_ai_scatter.png)

### Happiness by Region
The pie chart reveals regional disparities, with certain regions contributing disproportionately to higher happiness scores. 
This reinforces the understanding that global well-being is not evenly distributed.
![Happiness by Region](images/gen_ai_pie.png)

### Global Happiness Map
Finally, the global map visually connects economic strength and public health outcomes. 
The happier the country, the brighter it'll be on the map. 
Countries with high GDP per capita also display higher healthy life expectancy in the tooltip data, reflecting the intertwined nature of economic and social development.
![Global Happiness](images/gen_ai_choropleth.png)
