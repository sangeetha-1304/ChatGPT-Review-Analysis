# ChatGPT Review Analysis – Data Visualization Project
## 📌 Project Overview
This project analyzes *ChatGPT user reviews* using Python and visualizes key insights through *interactive and colorful data visualizations*.  
The goal is to understand *user sentiment, rating patterns, subjectivity levels, and frequently used positive keywords*.
This project is designed to be:
- Beginner-friendly
- Interview-ready
- Suitable for GitHub portfolio showcasing
## 🎯 Objectives
- Clean and preprocess review data
- Classify user sentiment based on ratings
- Analyze rating distribution
- Measure subjectivity from ratings
- Extract and visualize common positive keywords
- Create visually appealing charts and word clouds
## 🛠️ Technologies Used
- *Python*
- *Pandas* – Data manipulation
- *Matplotlib* – Data visualization
- *Seaborn* – Statistical visualizations
- *WordCloud* – Text visualization
- *Collections (Counter)* – Keyword frequency analysis
- *Regular Expressions (re)* – Text cleaning
## 📂 Dataset Information
- File Name: chatgpt_reviews (1).csv
- Contains user reviews and ratings related to ChatGPT usage
- Missing values and inconsistent formatting were handled during preprocessing
## 🔄 Data Cleaning & Preprocessing
- Converted column names to lowercase
- Handled missing review values
- Converted ratings to numeric format
- Created a sentiment column based on rating values
### Sentiment Logic:
- *Positive* → Rating ≥ 4
- *Neutral* → Rating = 3
- *Negative* → Rating ≤ 2
## 📊 Visualizations Included
### 1️⃣ Sentiment Distribution
- Shows the count of positive, neutral, and negative reviews
- Helps understand overall user opinion
### 2️⃣ Rating Distribution
- Histogram with KDE
- Displays how users rate ChatGPT
### 3️⃣ Rating vs Sentiment (Boxplot)
- Compares ratings across sentiment categories
- Highlights consistency of positive feedback
### 4️⃣ Subjectivity Score Distribution
- Subjectivity calculated as:nsubjectivity = rating / 5
- Shows how opinion-based the reviews are
### 5️⃣ Top Positive Keywords
- Extracted from positive reviews
- Visualized using:
- Colorful bar chart
- Word cloud
## ☁️ Word Cloud Visualization
- Generated using only positive reviews
- Highlights frequently used keywords
- Styled with modern color themes for better readability
## 🔍 Key Insights
- Majority of users have *positive sentiment* toward ChatGPT
- Higher ratings strongly align with positive reviews
- Reviews are largely *opinion-based*
- Common keywords reflect *helpfulness, ease of use, and productivity*
