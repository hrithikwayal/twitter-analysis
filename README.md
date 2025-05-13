# 🚀 Twitter Sentiment Analysis Project

This project performs sentiment analysis on tweets to determine the overall positivity, negativity, or neutrality of opinions expressed on Twitter about a specific topic. The analysis provides insights into public perception and emotional tone behind the tweets.

---

## 🛠️ Technologies Used

- **Python**: For scripting and data processing.
- **Tweepy**: To fetch tweets from the Twitter API.
- **TextBlob**: For sentiment analysis (polarity and subjectivity).
- **Pandas**: For data manipulation and analysis.
- **Matplotlib & WordCloud**: For data visualization.
- **Regex**: For text cleaning and preprocessing.

---

## 🌌 Twitter API Integration

The project integrates with the **Twitter API** to fetch tweets from a specified user's timeline. It collects the latest 100 tweets for analysis.

### 🔗 Twitter Developer Portal:
- [Twitter Developer Portal](https://developer.twitter.com/ )

### 🧾 Sample Tweet Data:
```json
{
  "tweet_id": 123456789,
  "full_text": "Example tweet text here...",
  "user": "editorji",
  "created_at": "2023-11-12",
  "language": "en"
}

```
## 🔄 Workflow Overview
- **Extract** : Fetch tweets using the Twitter API via Tweepy.
- **Transform** :Clean the tweets by removing mentions, hashtags, retweets, and hyperlinks.
Perform sentiment analysis using TextBlob to calculate polarity and subjectivity.
- **Load** : Store the processed data in a Pandas DataFrame for further analysis and visualization.
