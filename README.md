
# Company Perception Tool Using Sentiment Analysis

## Team Name - Intelligent Analyzers
Team Members:
- Atharv Chandratre - atharvc2@illinois.edu (Captain) 
- Uday Kanth Reddy Kakarla - uk3@illinois.edu
- Priyanka Awatramani - pma7@illinois.edu
- Ansh Bilimoria - amb20@illinois.edu

## Demo Video

<a href="http://www.youtube.com/watch?feature=player_embedded&v=sUQXYb06CcM" target="_blank">
 <img src="http://img.youtube.com/vi/sUQXYb06CcM/mqdefault.jpg" alt="Watch the video" width="240" height="180" border="10" />
</a>

[![Watch the video](https://img.youtube.com/vi/sUQXYb06CcM/default.jpg)](https://youtu.be/sUQXYb06CcM)

[![a](https://markdown-videos.deta/youtube/sUQXYb06CcM)](https://youtu.be/sUQXYb06CcM)

Note - Documentation is in the Documentation.pdf file in the root directory.

## How to use the code
Required software:
- Python 3
- Node

Run this to install the dependencies:

    pip install webdriver-manager selenium lzma numpy pandas nltk scikit-learn textblob statistics

### Scraper Usage
1.  Change the configuration variables which govern the number of companies the scraper will scrape for, and the number of reviews for each company which the scraper will extract. This can be found in the third cell of the Jupyter Notebook.  
    Note - do not set the number of reviews to scrape per company to over 150. Otherwise, indeed.com will block the scraper (by blocking your IP address for a cooldown period).
2.  Run all the cells in the Jupyter Notebook. There should be a run all cells button at the top of the IDE.
3.  Once all the cells have run, it will create your requested dataset in the present working directory.

### Sentiment Analyzer Usage

### Recommendation System Usage


## Idea Description

Sentiment analysis (or opinion mining) is a natural language processing (NLP) technique used to determine whether data is positive, negative, or neutral. Sentiment analysis is often performed on textual data to help businesses monitor brand and product sentiment in customer feedback, and understand customer needs. We scrape the company reviews’ data using our written scraper and then pre-process the data to tokenize the data and remove unnecessary tokens like stop words, punctuations, etc. We use NLTK (Natural Language Toolkit), a Python-based Natural Language Processing library for these tasks. We then use sentiment analysis on this data to help estimate employee satisfaction. We are using ‘emotion detection’ sentiment analysis, allowing us to go beyond polarity (i.e. very positive, positive, neutral, negative, very negative), to detect emotions, like happiness, frustration, anger, and sadness. Many emotion detection systems use lexicons (i.e. lists of words and the emotions they convey) or complex machine learning algorithms. We would be using the lexicon-based approach. We even developed a UI where a user can input a company name and we provide the score, positive/negative sentiment, and some recommendations on how to improve that satisfaction score.
