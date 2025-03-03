# Customer_Sentiment_Analysis
A Customer_Sentiment_Analysis Project by Python(Web Scrapping)
Customer Sentiment Analysis

📌 Project Overview

This project analyzes customer sentiment towards the iPhone 15 128GB model by scraping reviews from Flipkart. The goal is to extract insights about public perception, identify key product issues, and suggest potential improvements using sentiment analysis techniques.

🛠️ Tools & Libraries Used

Selenium: Automates web interactions to scrape product reviews.

BeautifulSoup: Parses HTML content for extracting review details.

Pandas: Handles data cleaning and preprocessing.

TextBlob: Performs sentiment analysis on review text.

Matplotlib & Seaborn: Visualizes sentiment distribution and key insights.

📂 Project Structure

Customer Sentiment Analysis/
│── data/                    # Folder for storing scraped review data
│── notebooks/               # Jupyter notebooks for analysis & visualization
│── src/                     # Python scripts for web scraping and analysis
│── README.md                # Project documentation
│── requirements.txt         # Dependencies for the project
│── sentiment_analysis.ipynb # Main Jupyter Notebook with full analysis

📥 Data Collection (Web Scraping)

Use Selenium to automate navigation to the Flipkart product page.

Extract Username, Rating, and Review Text using BeautifulSoup.

Handle pagination to collect at least 300 reviews.

🧹 Data Cleaning & Preprocessing

Remove duplicates and handle missing values.

Convert text to lowercase, remove special characters and stop words.

Apply lemmatization to standardize words.

📊 Sentiment Analysis

Use TextBlob to compute polarity scores.

Define classification criteria:

Positive Sentiment: Polarity ≥ 0.1

Negative Sentiment: Polarity < 0.1

📈 Insights & Visualization

Sentiment Distribution: Analyze the ratio of positive vs. negative reviews.

Rating vs. Sentiment: Identify correlations between ratings and sentiment scores.

Word Cloud: Highlight common words in positive & negative reviews.

Review Length Analysis: Assess if longer reviews convey stronger sentiment.

🚀 How to Run the Project

1️⃣ Install Dependencies

pip install -r requirements.txt

2️⃣ Run Web Scraping Script

python src/scraper.py

3️⃣ Perform Sentiment Analysis

jupyter notebook
# Open and run sentiment_analysis.ipynb

📌 Key Findings

Majority of reviews are positive, but some mention battery life issues.

Higher ratings correlate with positive sentiment, but some 4-star reviews highlight minor drawbacks.

The most common words in positive reviews: performance, camera, smooth.

The most common words in negative reviews: battery, heating, price.

🔍 Recommendations

Improve battery life and thermal management.

Address pricing concerns with discounts/offers.

Highlight camera performance in marketing campaigns.

📜 License

This project is open-source and available under the MIT License.

🤝 Contributing

Feel free to submit issues or pull requests to enhance the project!

📧 For any questions, reach out at suhailhasmi13@gmail.com

