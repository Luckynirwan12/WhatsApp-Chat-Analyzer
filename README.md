# 💬 WhatsApp Chat Analyzer 📊
A Streamlit web app that allows you to upload and analyze WhatsApp chat data with rich visualizations and statistics. Gain insights into message frequency, user activity, word usage, and even emojis — all in one dashboard!

---

## 🔗 Try It Out
👉 Colab Notebook: Open in Google Colab

👉 Streamlit App (if deployed): Live Demo

---

## 🚀 Features
- 📥 Upload .txt export of a WhatsApp chat

- 👤 Filter analysis by individual users or overall group

- 📈 Visualize:

   - Total messages, words, links & media shared

   - Monthly and daily activity timelines

   - Active days & months

   - Top contributors (users)
 
   - Most common words
   
   - Emoji usage insights
 
---

## 🛠️ Tech Stack
- Python 3

- Streamlit – for the web interface

- pandas – for data processing

- matplotlib – for visualizations

- emoji, urlextract – for text feature extraction

---

## 📁 Project Structure
📦 whatsapp-chat-analyzer/

├── app.py               # Streamlit web app logic

├── helper.py            # Analysis and statistics logic

├── preprocessor.py      # Raw chat text preprocessing

├── stop_hinglish.txt    # Stopwords list for word filtering

---

## 📄 How to Run Locally
1. Install dependencies:

       pip install streamlit
       pip install helper
       pip install processor
       pip install matplotlib

2. Run the app:

       streamlit run app.py

--- 

## 📂 How to Get WhatsApp Chat
1. Open WhatsApp Chat

2. Tap on the three-dot menu → More → Export Chat

3. Choose Without Media

4. Upload the .txt file in the app

---

## 🧪 How to Use
1. Export any WhatsApp chat (.txt file) from your phone (without media)

2. Open the app in Colab or Streamlit

3. Upload the chat file

4. View your chat's full statistics and visuals!

---
