# Fake-News-Intelligence-Dashboard
Detecting misinformation using Power BI + Python (TextBlob) with real-time sentiment insights.

# 📰 Fake News Intelligence Dashboard – Power BI + Python (NLP)

## 🔍 Overview
This is a hybrid data storytelling project combining **Power BI** with **Python-powered NLP (TextBlob)** to analyze and visualize patterns in fake vs real news.  
It explores trends by **source**, **category**, and **sentiment**, offering interactive insights into the emotional tone of online content.

---

## 📊 Features

- ✅ Fake vs Real news detection breakdown
- 🧠 Sentiment analysis (Positive, Neutral, Negative)
- 🗂️ Category-wise sentiment heatmap
- 📈 Sentiment score over time (line chart)
- 🗺️ Treemap of top fake news sources.
- 🎛️ Slicers for date, label, source, and category
- 💾 Dataset enhanced using Python  (TextBlob via Google Colab)

---

## 📁 Project Structure

Fake-News-Intelligence-Dashboard/
├── FakeNews_Intelligence_with_Sentiment.pbix
├── README.md
├── data/
│ └── FakeNewsDataset_withSentiment.csv
├── templates/
│ ├── FakeNewsDashboard_Original_Template.pbit
│ └── FakeNews_Sentiment_Template.pbit
├── screenshots/
│ └── dashboard_final.png

yaml
Copy
Edit

---

## 🧪 Sentiment Analysis (via Python)

Text sentiment was computed using **TextBlob** in Google Colab.  
Two new columns were added:
- `sentiment_score` → Numeric polarity (-1 to 1)
- `sentiment` → Label (Positive / Neutral / Negative)

The processed dataset was loaded into Power BI to enable dynamic sentiment visuals.

---

## 🛠 Tools Used

- Power BI Desktop
- Python (TextBlob + Pandas)
- Google Colab
- DAX Measures for KPIs
- Custom color schemes and slicers

---

## 🖼️ Screenshot

https://github.com/Harjeet-001/Fake-News-Intelligence-Dashboard/tree/main/screenshots

---

## 📦 How to Use

1. Clone or download this repo
2. Open `.pbix` in Power BI Desktop
3. Use slicers to explore sentiment by category, source, and label
4. View time-based sentiment score trends and fake news patterns

---

## 👤 Author

**S. Harjeet**  
🎓 Data Science Student – Kumaraguru College  
📫 harjeetgowda@gmail.com  
🔗 [LinkedIn](www.linkedin.com/in/harjeet-gowda-a04900337)
