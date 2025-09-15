Student Feedback Analysis – Internship Project
🎯 Overview

This project analyzes student feedback from college events (seminars, workshops, cultural fests) to extract actionable insights. The dataset was collected via Google Forms and exported as Excel/CSV. Using pandas, seaborn, matplotlib, and TextBlob, the project cleans the data, performs sentiment analysis, and visualizes patterns to help organizers improve future events.

🔑 Objectives

Clean and preprocess student feedback data

Analyze event ratings (1–5 scale)

Perform sentiment analysis on comments

Visualize insights with graphs, pie charts, and word clouds

Recommend improvements to event organizers

🛠 Tools & Libraries

Google Colab / Jupyter Notebook – Execution environment

pandas – Data cleaning and manipulation

matplotlib / seaborn – Visualization

TextBlob / VADER – Sentiment analysis (NLP)

wordcloud – Most frequent words in comments

📂 Dataset

Source: Google Form survey (student responses after events)

Columns include:

Timestamp – Submission time

Department – Student’s department

Event Name – Name of the event attended

Rating (1–5) – Satisfaction rating

Comments – Written feedback

📊 Key Insights Generated

Distribution of event ratings

Average satisfaction per department/event

Sentiment polarity of comments (Positive / Neutral / Negative)

Most common words in student feedback (word cloud)

Correlation between ratings and event type

📁 Project Structure
📦 Student-Feedback-Analysis
 ┣ 📜 Student feedback analysis.ipynb   # Main Jupyter Notebook
 ┣ 📜 student_feedback.xls              # Sample dataset
 ┣ 📜 README.md                         # Project documentation
 ┗ 📂 outputs/                          # Graphs, word clouds, insights

🚀 How to Run

Clone this repository or upload the notebook to Google Colab

Install dependencies (if needed):

pip install pandas matplotlib seaborn textblob wordcloud


Open Student feedback analysis.ipynb

Run cells step by step to see:

Cleaned dataset

Sentiment scores

Visualizations & insights

🧠 Skills Learned

Data cleaning with pandas

Sentiment analysis with TextBlob

Visualization with matplotlib & seaborn

Word cloud generation

Practical application of data science to real feedback

📌 Deliverables

Well-commented Jupyter Notebook

Charts & word cloud visualizations

Mini-report with recommendations
