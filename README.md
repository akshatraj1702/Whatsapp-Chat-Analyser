# 📱 WhatsApp Chat Analyzer

A Python-based WhatsApp Chat Analyzer that converts exported WhatsApp chats into meaningful statistics and visual insights using Pandas, Matplotlib, Seaborn, WordCloud and Streamlit.

## 🚀 Features

- **Overall Statistics**
  - Total messages
  - Total words
  - Total media shared
  - Total links shared

- **User Analysis**
  - Most active users
  - Individual user analysis
  - Percentage contribution of each user

- **Timeline Analysis**
  - Monthly messaging timeline
  - Daily messaging timeline

- **Activity Analysis**
  - Most active days of the week
  - Most active months
  - Weekly activity heatmap
  - Hour-wise messaging patterns

- **Text Analysis**
  - Most commonly used words
  - Word cloud visualization

- **Emoji Analysis**
  - Most frequently used emojis
  - Emoji frequency visualization

## 🛠️ Tech Stack

- Python
- Pandas
- Streamlit
- Matplotlib
- Seaborn
- Regex
- WordCloud
- URLExtract

## ⚙️ Project Workflow

1. Upload an exported WhatsApp `.txt` chat.
2. Read and decode the uploaded file.
3. Use Regex to identify timestamps and messages.
4. Separate the date, time, user and message.
5. Convert the raw data into a Pandas DataFrame.
6. Create additional features such as:
   - Year
   - Month
   - Day
   - Day name
   - Hour
   - Time period
7. Pass the processed DataFrame to the analysis functions.
8. Calculate messaging statistics and user activity.
9. Generate visualizations using Matplotlib, Seaborn and WordCloud.
10. Display the results through an interactive Streamlit dashboard.

## 📂 Project Structure

```text
whatsapp-chat-analyzer/
│
├── app.py                  # Streamlit application
├── preprocessor.py         # Data cleaning and preprocessing
├── helper.py               # Analysis functions
├── stop_hinglish.txt       # Stop words
├── requirements.txt        # Project dependencies
└── README.md               # Project documentation
