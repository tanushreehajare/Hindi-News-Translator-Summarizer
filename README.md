# 📰 Hindi News Translator & Summarizer

> "Breaking language barriers with AI-powered news translation & summarization 🔥"

## 🌟 Overview  

This project scrapes Hindi news articles from the web, translates them into English, and generates concise summaries using **Natural Language Processing (NLP)**. Leveraging **web scraping, machine translation, and deep learning**, it enhances accessibility to Hindi news for non-Hindi speakers. 🚀  

---

## 💡 Features  

🔍 **Web Scraping** – Extracts news articles (title, date, content)  
🌎 **Translation** – Converts Hindi text into English using **GoogleTrans**  
📝 **Summarization** – Uses **BART Transformer** to generate a short, meaningful summary  
⚡ **Fast & Automated** – Fetches, translates, and summarizes news in seconds  

---

## 🛠️ Tech Stack  

- **Programming Language**: Python 🐍  
- **Libraries**:  
  - BeautifulSoup 🌐 (Web Scraping)  
  - GoogleTrans 🌍 (Translation)  
  - Transformers 🤖 (NLP & Summarization)  
  - Requests 📡 (Fetching News Content)  
- **Model Used**: BART (Pre-trained for Summarization)  

---

## ⚙️ How It Works  

1️⃣ **Scrape News Articles** – Fetches article title, date, and content  
2️⃣ **Translate to English** – Converts Hindi text into English using `googletrans`  
3️⃣ **Summarize the Article** – Uses a **pre-trained BART model** to generate a concise summary  
4️⃣ **Display Output** – Shows the original article, translation, and summary  

---

## 🚀 Installation & Usage  

### 1️⃣ Install Dependencies  
```bash
pip install requests beautifulsoup4 googletrans==4.0.0-rc1 transformers
