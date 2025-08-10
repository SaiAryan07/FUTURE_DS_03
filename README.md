# FUTURE_DS_03
# 📊 Student Feedback Dashboard – Task 3 (Data Science & Analytics Internship)

## 📌 Overview
This project is part of my *Data Science & Analytics Internship at Future Interns*.  
The goal of Task 3 was to analyze *student feedback data* and build a *Power BI dashboard* to uncover key insights about ratings, sentiment, and performance of various aspects of the course.
## 📷 Dashboard Preview
![Dashboard Preview](dashboard_screenshot.png)  
(https://github.com/SaiAryan07/FUTURE_DS_03/blob/main/Dashboard.png)
## 🎯 Objectives
- Process raw feedback data into a structured format.
- Categorize ratings into *Positive, **Neutral, and **Negative* sentiments.
- Identify the *Top Rated* and *Least Rated* questions.
- Visualize the *distribution of ratings* and *sentiment analysis*.
- Provide an interactive dashboard for data-driven decisions.
## 🛠 Tools & Technologies
- *Power BI Desktop* – for data modeling and visualization.
- *Power Query* – for data cleaning and transformation.
- *DAX (Data Analysis Expressions)* – for calculated measures.
- *CSV Dataset* – student feedback data.
## 📂 Dataset Details
The dataset contains:
- *Question* – Feedback questions asked to students.
- *Rating* – Numeric ratings (1–10 scale).
- *Sentiment* – Derived column based on rating:
  - Negative → Rating ≤ 4  
  - Neutral → Rating 5 to 7  
  - Positive → Rating 8 to 10
## ❓ Why Sentiment Analysis (NLP) Was Not Used
The dataset provided for Task 3 contained *only numeric ratings* (1–10) without any open-ended text feedback.  
Since sentiment analysis in the traditional NLP sense requires textual comments (e.g., "The course was great" or "The assignments were too hard"), applying NLP was not possible.
Instead, sentiment was derived *directly from the numeric ratings* using predefined thresholds:
- *Negative* → Rating ≤ 4  
- *Neutral* → Rating 5 to 7  
- *Positive* → Rating 8 to 10  
This allowed us to still capture sentiment distribution while working within the limitations of the dataset.
## 📊 Dashboard Features
### *Key Metrics*
- *Sum of Ratings*
- *Average Rating*
- *Maximum & Minimum Rating*
- *Top Rated Question*
- *Least Rated Question*
### *Visualizations*
1. *Average Rating by Question* – Bar chart showing rating trends.
2. *Sum of Ratings by Sentiment* – Pie chart of sentiment distribution.
3. *Sentiment Breakdown by Question* – Stacked column chart.
4. *Negative, Neutral, Positive Counts Table* – Detailed sentiment count for each question.
5. *Distribution of Ratings* – Filter-aware visualization.
## 📈 Insights
- *"Well versed with the subject"* had the highest average rating (7.50).
- *"Course recommendation based on relevance"* had the lowest average rating (5.60).
- Overall feedback was *48.8% Positive, **36.8% Neutral, and **14.4% Negative*.
- Sentiment breakdown per question helps identify areas of improvement.
## 📌 Author
*Meesala 
Sai Aryan*  
[GitHub Profile](https://github.com/SaiAryan07) |
[LinkedIn Profile](https://www.linkedin.com/in/YOUR-LINKEDIN-ID)
