# Sentiment Analysis with Text Mining using Python & R

This project applies **text mining** and **sentiment analysis** techniques on YouTube user comments related to **Shell gas stations**, using both **Python** and **R** programming languages. It aims to extract customer perceptions and emotional tendencies to gain actionable insights from unstructured text data.

## 📌 Project Objective

To analyze YouTube comments to:

- Understand customer opinions on Shell gas stations
- Detect common emotions and polarity in customer feedback
- Provide a foundation for service quality improvement using real-world data

## 🛠 Tools & Technologies

- **Python**  
  - Used for data scraping from YouTube using YouTube API
- **R**  
  - Text preprocessing  
  - Word cloud generation  
  - Emoji analysis  
  - Sentiment analysis (`get_nrc_sentiment`)  
  - Polarity classification and visualization (`ggplot2`)

## 🧾 Dataset

- Comments were collected from the following video:  
  [Shell Akaryakıt İstasyonları | YouTube](https://www.youtube.com/watch?v=8uIsbRaArvk)

## 🔍 Main Steps

### Python
- Extracted YouTube comments using API
- Stored in structured format (CSV)

### R
- Preprocessing:
  - Lowercasing, stopword removal, punctuation stripping
  - Emoji extraction and cleaning
- Word frequency analysis
- Emoji frequency and cloud visualization
- **Sentiment Analysis**:
  - Emotions (anger, joy, fear, etc.) using NRC lexicon
  - Barplot visualization
- **Polarity Analysis**:
  - Labeling as positive, negative, or neutral
  - Frequency and proportion charts

## 📊 Visualizations

- Word Cloud
- Emoji Cloud
- Emotion Distribution Bar Chart
- Polarity Pie Chart

## 📈 Outcomes

- Dominant emotional tones: `joy` and `trust`
- Most frequent emojis and keywords revealed consistent positive feedback
- Useful insights for Shell's customer experience and brand perception

## 📚 References

- Torun, N. K. & Şengül, A. (2022). *Text Mining of Cryptocurrency Tweets*.  
  Int. Journal of MIS & Computer Science, 6(1), 54-65.
- Medium Article: [Using APIs in Data Science](https://medium.com/@seherkumsar/veri-biliminde-api-kullanımı-7b21aa28f3d9)
- Newslab Turkey: [Text Mining in R](https://www.newslabturkey.org/2019/10/16/r-ekosisteminde-metin-madenciligi-nasil-yapilir/)

## 👤 Author

**Tunahan Karasakal**  
Bilecik Şeyh Edebali University – Management Information Systems  
Supervised by: **Assoc. Prof. Dr. Nur Kuban Torun**

---

> 🔖 _This repository demonstrates an end-to-end NLP pipeline using both Python and R to analyze real user-generated content._

