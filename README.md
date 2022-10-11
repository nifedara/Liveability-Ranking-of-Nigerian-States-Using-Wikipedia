# Liveability-Ranking-of-Nigerian-States-Using-Wikipedia
## Analyzing Wikipedia data using NLP and Machine Learning ##

by **https://github.com/nifedara**

### 💡 Inspiration 💡
1. Moving to a new place can be daunting, so we often desire to know the condition of the place before there. This can guide our decision and evaluate things to prepare for.
2. Local quality of life and liveability of our environment has been a major concern of late. And we need Policymakers to make urgent decisions that will improve citizens living conditions.
   But how do we measure the quality of our environment in a country where getting data can be very tedious? 

### 💡 Objectives 💡 ###
1. extract Wikipedia articles about some Nigerian states
2. do a liveability ranking of the states based on the characteristics of the articles and across 4 indicators(Education, Environment, Infrastructure and Health).
3. determine whether Wikipedia articles can be used to estimate the development of regions of the world where the United Nations Sustainable Development Goals are hard to track due to a lack of data. 


### 🔨👩🏾‍💻 Installation 👩🏾‍💻🔨 ###
1. Pandas - for data cleaning/manipulation
2. spaCy and NLTK (Natural Language Toolkit) - for text analysis
3. Sklearn - for machine learning
4. TextBlob - for sentiment analysis
5. MatPlotlib - for visualization
6. WordCloud - for Word Cloud visualization
7. Geopandas - for working with geospatial data

### ❔ QUESTION ❔ ###
: Where are the worst and most liveable places in Nigeria?
> To answer this, I carried out an analysis of over 55474 Wikipedia articles that mention Nigeria.

### ⚙️ Project Methodology ###
The approach I used in this analysis to find out the liveability of states in Nigeria by mining Wikipedia is categorized into the following phases;
1. Getting Data - Wikipedia Extraction (XML Parsing)
2. Named Entity Recognition
3. Machine Learning Classification
4. NLP Pre-processing
5. Sentiment Analysis
6. Liveability Scoring and Ranking

### 👩🏾‍💻 Result ###

From the results, the following deductions were made:
1. Of the 10 Nigerian states considered, Anambra state is the most liveable state.
2. Akwa-Ibom state is the least liveable state.

#### Success Metric: ####
80% Similarity of my liveabilty result to the 2019 HDI(Human Development Index) Ranking of Nigerian states


There's no previously done Nigerian state liveabilty ranking metric to measure the accuracy of the result of my analysis with, but I believe Wikipedia articles can be used to estimate the development of regions of the world, like Nigeria where the United Nations Sustainable Development Goals are hard to track due to a lack of data.


### Dataset ###
The dataset of the Wikipedia articles about Nigeria which I created will be uploaded for access to anyone who is interested in a project like this.
