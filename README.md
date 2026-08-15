WhatsApp Chat Analyzer

A simple Streamlit-based WhatsApp Chat Analyzer that turns an exported WhatsApp chat into useful insights and visualizations.

What it does
📊 Shows total messages, words, media and links shared
📈 Analyzes monthly and daily messaging activity
👥 Finds the most active users
📅 Shows the busiest days and months
🔥 Creates a weekly activity heatmap
☁️ Generates a word cloud
🔤 Finds the most commonly used words
😂 Analyzes emoji usage

How it works?

The project is split into three main parts:

preprocessor.py – cleans the raw WhatsApp chat and converts it into a structured Pandas DataFrame.
helper.py – performs the actual analysis on the DataFrame.
app.py – handles the Streamlit interface and displays the results as charts and tables.
