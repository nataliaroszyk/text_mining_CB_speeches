# Text Mining on Central Bank Speeches

## Project Team

Natalia Roszyk (Miela), 
Pola Parol, 
Irena Zimovska

## Project Overview

This project focuses on the analysis of central bank speeches using text mining techniques. The dataset, sourced from Kaggle's "Central Bank Speeches," includes numerous speeches from senior central bankers. These speeches are pivotal as they can significantly influence economic conditions. Central banks, being the authorities on monetary policy, play a crucial role in financial markets. The speeches by central bankers, therefore, receive extensive scrutiny and analysis. For our project we filtered speeches from the United States, spanning from 1997 to 2022.

## Dataset

The dataset used in this project is available on Kaggle under the title "Central Bank Speeches." It compiles speeches from senior central bankers, highlighting the impact of their words on economic policies and market movements.

Dataset Source: Central Bank Speeches on Kaggle https://www.kaggle.com/datasets/davidgauthier/central-bank-speeches


## Notebook Content

### Methodology

Data Loading and Preprocessing: Libraries used include pandas, nltk, matplotlib, seaborn, sklearn, and more. Data cleaning involved handling missing values, tokenization, and lemmatization.  

Exploratory Data Analysis (EDA): Initial exploration involved analyzing speech lengths, distributions, and basic textual content.  

Text Mining Techniques: Application of TF-IDF Vectorization, word clouds, and NLP techniques to analyze and visualize the content and themes of the speeches. Sentiment analysis was conducted to assess the tone and sentiment of the speeches over time and for a specific author.  

Text Clustering: Utilized MiniBatchKMeans to cluster speeches into thematic groups, revealing predominant topics such as monetary policy, financial risk, and regulatory supervision.  

Sentiment Analysis: Employed TextBlob to analyze the sentiment of the speeches, identifying patterns and trends in sentiment over time and for a specific author.  

Authorship Analysis: Analyzed writing styles and thematic focus of different authors through TF-IDF Vectorization.
Impact Analysis: Explored the potential impact of speech sentiments on the S&P 500 index, although findings were inconclusive due to the complex interplay of market factors.  

### Key Findings

The clustering identified distinct themes such as monetary policy, financial risks, and regulatory practices.
Sentiment analysis revealed fluctuations in sentiment over time, correlating with significant economic events.
Authorship analysis highlighted differences in thematic emphasis among central bankers.

## Requirements

To run this project, you will need Python and the following packages installed:

- pandas for data manipulation and analysis
- nltk (Natural Language Toolkit) for text processing and sentiment analysis
- matplotlib and seaborn for data visualization
- sklearn for implementing machine learning methods, including TF-IDF Vectorization and MiniBatchKMeans clustering
- wordcloud for generating word clouds
- textblob for conducting sentiment analysis
- numpy for numerical computations
- scipy for scientific computing and statistical analysis

After installing the required Python packages, you will need to download additional data used by the `nltk` package for processing text. This includes sets of stopwords and the WordNet lemmatizer data. You can do this by running the following Python commands:

```python
import nltk
nltk.download('stopwords')
nltk.download('wordnet')
```

