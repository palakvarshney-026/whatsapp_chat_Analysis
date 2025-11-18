📱 WhatsApp Chat Analysis

A data analysis project that processes exported WhatsApp chats to generate insights such as message frequency, user activity, most used words, media statistics, and more.

📌 Project Overview

This project analyzes a WhatsApp chat exported as a .txt file and converts it into meaningful visual insights. It helps identify:

👤 Most active users

🕒 Daily / Monthly message timelines

💬 Most used words

😂 Emoji analysis

📎 Media & link sharing stats

📊 Hourly activity heatmap

📂 Project Structure
|-- app.py              # Main Streamlit web app
|-- helper.py           # Functions for statistics & visualizations
|-- preprocessor.py     # Chat cleaning & preprocessing logic
|-- chat.txt            # Sample WhatsApp chat file (exported)
|-- README.md           # Project documentation

🛠️ Technologies Used

Python

Pandas

Matplotlib / Seaborn / Plotly

Streamlit

Emoji library

Regex (for chat cleanup)

🎯 Features

✔ Upload and analyze WhatsApp chat (.txt)
✔ Automatic preprocessing (date, time, message, user separation)
✔ Daily, monthly, and weekly timelines
✔ User-wise message distribution
✔ Most common words visualization
✔ Emoji usage frequency
✔ Media and link sharing count
✔ Heatmap of message activity
