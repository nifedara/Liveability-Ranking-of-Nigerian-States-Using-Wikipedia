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
The approach used in this analysis to find out the liveability of states in Nigeria by mining Wikipedia is categorized into the following phases;
1. Getting Data - Wikipedia Extraction (XML Parsing)
2. Named Entity Recognition
3. Machine Learning Classification
4. NLP Pre-processing
5. Sentiment Analysis
6. Liveability Scoring and Ranking

### 👩🏾‍💻 Result ###

From the results, the following deductions were made:
1. Of the 10 Nigerian states considered, Lagos state ranked as the most liveable state.
2. Imo state had the highest score in the infrastructure liveability category. And ranked the second most liveable state.
3. Kano state ranked as the least liveable state of the 10 states considered.
4. Kaduna state is at the bottom of the rank, just a position above Kano

#### 🚀 Success Metric: ####
***80% Similarity of the liveabilty ranking result to the 2019 HDI(Human Development Index) Ranking of Nigerian states.***

Comparing the 2019 HDI(Human Development Index) Ranking of Nigerian states (list by Radboud University) to my liveability ranking result, there is a close similarity. In my liveability ranking, Lagos ranked the highest, and Kaduna and Kano ranked the least, just like in this HDI ranking

#### 🎙 Conclusion: ####
Wikipedia articles can be used to estimate the development of regions of the world, like Nigeria where the United Nations Sustainable Development Goals are hard to track due to a lack of data.

### 🚀 Next ###
* The output can be used in recommendation systems.
* Can also bbe used in reports of the progress in achieving SDGs


### Dataset ###
The data used can be gotten by mining Wikipedia articles.
