# 📊 Customer Sentiment Analysis on iPhone 15 128GB

## 📌 Project Overview

This project performs **customer sentiment analysis** on user reviews of the **iPhone 15 128GB** collected from **Flipkart**. The goal is to evaluate public perception by analyzing the sentiment behind customer reviews. The findings can help Amazon understand customer feedback patterns, drive strategic decisions, and enhance customer satisfaction.

---

## 🚀 Project Workflow

### 1️⃣ Data Collection (Web Scraping)
- **Tools Used:** Selenium, BeautifulSoup
- **Objective:** Scrape 300+ customer reviews from Flipkart, including:
  - **Username**
  - **Rating** (1-5 stars)
  - **Review Text**
- **Features:** Pagination handling to gather reviews from multiple pages.

---

### 2️⃣ Data Cleaning and Preprocessing
- **Tools Used:** Pandas, NLTK
- **Steps:**
  - Remove duplicate reviews
  - Handle missing values
  - Text Preprocessing:
    - Convert to lowercase
    - Remove punctuation/special characters
    - Tokenization and stop words removal
    - Lemmatization

---

### 3️⃣ Sentiment Analysis
- **Tool Used:** TextBlob
- **Methodology:**
  - Calculate **polarity score** for each review:
    - **Positive Sentiment:** Polarity ≥ 0.1
    - **Negative Sentiment:** Polarity < 0.1
  - Classify and store sentiment results

---

### 4️⃣ Data Analysis & Insights
- **Tools Used:** Pandas, Matplotlib, Seaborn, WordCloud
- **Analysis Includes:**
  - Sentiment distribution visualization
  - Rating vs. sentiment polarity analysis
  - Word clouds for positive and negative reviews
  - Review length vs. sentiment analysis

---

### 5️⃣ Reporting
- Key findings from sentiment analysis
- Insights and trends
- Recommendations for product improvement and marketing

---

## 📦 Libraries and Tools Used
- `Selenium`
- `BeautifulSoup`
- `Pandas`
- `NLTK`
- `TextBlob`
- `Matplotlib`
- `Seaborn`
- `WordCloud`

---

## 📌 Key Insights

- 📈 70%+ reviews show positive sentiment, reflecting overall customer satisfaction with the iPhone 15 128GB.
- ⭐ Higher star ratings (4 & 5 stars) correlate strongly with positive sentiment polarity.
- 📷 Camera quality, 💎 display performance, and ⚡ overall speed are the most praised features.
- 🔋 Battery life, 💰 high pricing, and 🚚 delivery issues are common points in negative reviews.
- ✍️ Longer reviews tend to convey more detailed sentiments, whether strongly positive or negative.

---

## ✅ Recommendations

- ✅ Focus marketing campaigns on camera performance, display quality, and overall user experience to attract new customers.
- ✅ Address battery-related issues in future updates or models to reduce negative feedback.
- ✅ Consider pricing strategies or offers to tackle price-related complaints.
- ✅ Improve delivery and post-purchase service to minimize dissatisfaction due to logistical delays.
- ✅ Encourage detailed customer reviews for richer sentiment analysis and better understanding of user needs.
- ✅ Use frequently mentioned positive keywords in product listings to reinforce positive perceptions.

---

## 👨‍💻 Author

**Shekhar Mishra**

---

## 📝 How to Run

```bash
# Clone the repository
git clone https://github.com/yourusername/your-repo-name.git

# Install dependencies
pip install -r requirements.txt

# Run the Jupyter Notebook
jupyter notebook
```bash

---

## 👨‍💻 Author

**Shekhar Mishra**
