📊 Customer Sentiment Analysis on iPhone 15 128GB
📌 Project Overview
This project performs customer sentiment analysis on user reviews of the iPhone 15 128GB model collected from Flipkart. The goal is to evaluate public perception by analyzing the sentiment behind customer reviews. The findings can help Amazon understand customer feedback patterns, drive strategic decisions, and enhance customer satisfaction.

🚀 Project Workflow
1️⃣ Data Collection (Web Scraping)
Tools Used: Selenium, BeautifulSoup

Objective: Scrape 300+ customer reviews from Flipkart, including:

Username

Rating (1-5 stars)

Review Text

Features: Pagination handling to gather reviews from multiple pages.

2️⃣ Data Cleaning and Preprocessing
Tools Used: Pandas, NLTK

Steps:

Remove duplicate reviews

Handle missing values

Preprocess text:

Convert to lowercase

Remove punctuation/special characters

Tokenize and remove stop words

Perform lemmatization

3️⃣ Sentiment Analysis
Tool Used: TextBlob

Methodology:

Calculate polarity score for each review:

Positive: Polarity ≥ 0.1

Negative: Polarity < 0.1

Classify and store sentiment results

4️⃣ Data Analysis & Insights
Tools Used: Pandas, Matplotlib, Seaborn, WordCloud

Analysis Performed:

Sentiment distribution visualization

Relationship between star ratings and sentiment polarity

Word clouds for positive and negative reviews

Review length vs sentiment analysis

5️⃣ Reporting
Detailed insights from sentiment analysis

Key trends and recommendations for product improvements and marketing focus areas

📦 Libraries and Tools Used
Selenium

BeautifulSoup

Pandas

NLTK

TextBlob

Matplotlib

Seaborn

WordCloud

👨‍💻 Author
Shekhar Mishra

