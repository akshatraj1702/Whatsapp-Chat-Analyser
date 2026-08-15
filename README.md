WhatsApp Chat Analyzer

A simple end-to-end WhatsApp Chat Analyzer built with Python and Streamlit. The project takes an exported WhatsApp chat and converts it into meaningful statistics and visual insights about the conversation.

Features
Total messages, words, media and links shared
Monthly and daily messaging timelines
Most active users in the group
Busiest days and months
Weekly activity heatmap
Most commonly used words
Word cloud of frequently used words
Emoji usage analysis

How It Works?

The project is divided into three main modules:

preprocessor.py
Parses the raw WhatsApp .txt file, separates users and messages, converts timestamps, and creates useful date/time features.

helper.py
Contains the analysis functions used to calculate statistics, user activity, word frequencies, emojis, timelines and other insights.

app.py
Handles the Streamlit interface, user selection and visualization of the analysis results.
