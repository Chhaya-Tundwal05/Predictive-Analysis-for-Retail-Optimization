
# GAP Inc. Case study Analysis Notebooks

This repository contains independent Jupyter notebooks that each analyze for different fashion brands, using data from various sources like Amazon, Reddit, and online reviews. The notebooks are not linked to each other and serve as standalone analyses for specific brands.

## Table of Contents
1. Overview
2. Notebooks
3. Data Sources
4. Dependencies
5. How to Run

## Overview
Each notebook in this repository performs analysis on a different fashion brand. The analyses aim to extract customer sentiment from reviews and provide insights into customer perceptions of these brands. 

## Notebooks

- **team_6_GAP_Amazon.ipynb**: This notebook analyzes Amazon reviews for Gap Inc. It provides an overview of customer sentiment and identifies key themes in the reviews.
  
- **team_6_GAP_Reviews.ipynb**: A sentiment analysis of customer reviews from various sources for Gap Inc. The notebook includes an analysis of review texts, sentiment distribution, and potential areas for improvement.

- **team_6_Old_Navy_Reviews.ipynb**: This notebook focuses on customer reviews for Old Navy, performing sentiment analysis to understand customer satisfaction and feedback trends.

- **team_6_BR_Reviews.ipynb**: Sentiment analysis for Banana Republic, using reviews from multiple platforms to understand customer perceptions and identify common themes in feedback.

- **team_6_Reddit_Analysis.ipynb**: Analysis of Reddit discussions related to fashion brands, focusing on mentions of Old Navy, Gap Inc., and Banana Republic. The analysis looks at sentiment in Reddit posts and comments.

**team_6_Zara.ipynb**: This notebook contains sentiment analysis of Zara reviews. It explores customer opinions and sentiment distribution from online review sources.

## Data Sources
The data used for each notebook comes from various online platforms, which may include:
- **Amazon**: Customer reviews for brands like Gap Inc.
- **Reddit**: Posts and discussions from relevant subreddits such as Old Navy and fashion-related subreddits.
- **Online Review Platforms**: Feedback and reviews from customers for brands like Old Navy, Banana Republic, and Zara.

## Dependencies
The notebooks rely on the following Python libraries for data manipulation, sentiment analysis, and visualization:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `nltk` (for natural language processing)
- `scikit-learn`
- `beautifulsoup4` (for web scraping, if applicable)
- `praw` (for Reddit API access, if applicable)

Each notebook may have slightly different dependencies depending on the source of data and the type of analysis performed.

## How to Run
# 1. Scrapping Reviews
    1.1 Old Navy Reviews (team_6_Old_Navy_reviews.ipynb)
        - Scraping the reviews 
            - Selenium should be installed
            - Chrome web driver should be installed
            - after scraping reviews are saved in file named "oldnavy_reviews.csv"
        - Sentiment Analysis using Azure API
            - Define your Azure Text Analytics credentials
            - Replace the endpoint and key with your specific azure credentials
        - Run the file : team_6_Old_Navy_reviews.ipynb
        - Output will be stored in "oldnavy_reviews_with_sentiment.csv"
        - Ploting Graphs using the above csv file and further analysis
    1.2 Gap Reviews (team_6_GAP_Reviews.ipnyb)
        - Scraping the reviews 
            - Selenium should be installed
            - Chrome web driver should be installed
            - after scraping reviews are saved in file named "gap_reviews.csv"
        - Sentiment Analysis using Azure API
            - Define your Azure Text Analytics credentials
            - Replace the endpoint and key with your specific azure credentials
        - Run the file : team_6_GAP_Reviews.ipnyb
        - Output will be stored in "gap_reviews_with_sentiment.csv"
        - Ploting Graphs using the above csv file and further analysis
    1.3 Banana Republic Reviews (team_6_BR_reviews.ipynb)
        - Scraping the reviews 
            - Selenium should be installed
            - Chrome web driver should be installed
            - after scraping reviews are saved in file named "bananarepublic_reviews.csv"
        - Sentiment Analysis using Azure API
            - Define your Azure Text Analytics credentials
            - Replace the endpoint and key with your specific azure credentials
        - Run the file : team_6_GAP_Reviews.ipnyb
        - Output will be stored in "br_reviews_with_sentiment.csv"
        - Ploting Graphs using the above csv file and further analysis
    1.4 Reddit Reviews Analysis for all 3 brands(team_6_Reddit_Analysis.ipynb)
        - install praw using `pip install praw`
        - Use the below Reddit API credentials
            client_id = 'Fyqn_6HWARai8q76-5T2mQ'
            client_secret = 'yNFP5YkphGEkusSa6uY958hKGJDqeQ'
            user_agent = 'WDAscrapper'
        - Sentiment Analysis using Azure API
            - Define your Azure Text Analytics credentials
            - Replace the endpoint and key with your specific azure credentials
        - Run the file : team_6_Reddit_Analysis.ipnyb
# 2. Scrapping of Amazon (team_6_GAP_Amazon.ipynb)
    - Selenium should be installed
    - Chrome web driver should be installed 
    - Run the file : GAP_AMazon.ipynb
    - Results will be stored in "GAP_Amazon_Listings.csv"
# 3. Google Trend Analysis (team_6_Google_Trends_Analysis.ipynb)
    - Loading the 'shopping_trends_updated.csv' data file
    - Run the Google_Trends_Analysis.ipynb file
# 4. Zara - Regression Analysis (team_6_Zara.ipynb)
    - Loading the 'fashion_data_2018_2022.csv' data file
    - Run the team_6_Zara.ipynb file
Each notebook can be run independently by executing the cells in order.

## Conclusion
These notebooks provide standalone analyses for various fashion brands. Each analysis offers unique insights into customer reviews and feedback for the specific brand, helping identify areas for potential improvement or marketing focus.

## Team Members : Chhaya Tundwal, Tirth Patel, Tomas Mujica

