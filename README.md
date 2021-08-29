# Data-Science-Soccer-Football
Data Science project where I use ML models to predict soccer/football player market values

### Background:
There has been a steady rise in the overall prices of players in soccer/football throughout the years, and what comes with that is the criticism towards top clubs for 'overspending' on certain players. In order to have a more objective view of whether a player is overvalued/undervalued, I wanted to create a machine learning model that predicts the market value of a player based on their stats.

## Skills Demonstrated:
Web Scraping (BeautifulSoup), Data Cleaning (pandas), Data Visualization (Matplotlib, Seaborn, Plotly), K-means Clustering, Permutation/Feature Importance,
Shap plots, XGBoost, Neural Networks (Tensorflow, Keras)

#### FB_Reference_Datasets
Player stats datasets of 2020-2021 season taken from https://fbref.com/en/
#### Transfermarkt Datasets
Player market value datasets of 2020-2021 season webscraped from https://www.transfermarkt.co.uk/
## Notebooks 
#### Clean_Transfermarkt_Data.ipynb:
Clean transfermarkt dataset
#### Clustering.ipynb:
Perform K-Means Clustering to classify player prototypes beyond player position
#### Market_Value_Prediction_Model.ipynb:
Use XGBoost and Neural Networks (Tensorflow/Keras) to create soccer/football player market value prediction model
#### Preprocessing_Data.ipynb:
Clean datasets and merge them before modeling
#### WebScrape_Transfermarkt.ipynb:
Webscrape market value data from https://www.transfermarkt.co.uk/
