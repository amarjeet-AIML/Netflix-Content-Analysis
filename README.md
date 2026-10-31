🎬 Netflix Global Content & Viewership Analysis

An end-to-end Data Analytics study exploring global audience engagement, content distribution,
language trends, and release timing strategies using official Netflix viewing data.

📌 Project Overview

Netflix periodically releases global engagement data covering thousands of catalog titles.
This project utilizes Python, Pandas, Matplotlib, and Seaborn to perform comprehensive Exploratory Data Analysis (EDA) on total hours viewed.

By analyzing engagement across content formats, languages, global availability, and release calendars, this study delivers
data-driven insights to evaluate content acquisition ROI and platform scheduling strategies.

🎯 Objectives

Top 10 Performance: Identify and analyze the highest-grossing titles globally by total viewing hours.

Format Engagement (Movies vs. Shows): Evaluate total aggregate watch time and average viewing hours per title across formats.

Global Availability Impact: Assess viewership differentials between globally licensed content and regionally restricted titles.

Language & Market Breakdown: Measure total viewership across English, Korean, Japanese, Spanish, and Hindi titles.

Release Timing Analysis: Identify optimal release days and yearly trends that maximize initial 72-hour viewer activity.

📊 Key Insights & Analytical Findings

Dimension

Key Finding

Data Metric

Format Dominance

TV Shows account for the majority of total engagement due to multi-episode binge structures.

107.43B hours (68%) vs. 50.54B hours (32%) for Movies.

Average Engagement

TV Show seasons generate significantly higher average watch time per title than Movies.

10.29M avg hrs/show vs. 3.63M avg hrs/movie (2.8x multiplier).

Catalog Distribution

Top 10 blockbusters drive excitement, while the long-tail catalog maintains overall user retention.

Top 10 = 3.52% (5.56B hrs); Catalog = 96.48% (152.41B hrs).

Global Licensing

Simultaneous global distribution substantially lifts viewership compared to localized licensing.

11.39M avg hrs (Global) vs. 4.32M avg hrs (Restricted) (2.64x lift).

Language Crossover

Non-English titles achieve exceptional international popularity and engagement ROI.

English: 124.09B hrs | Korean: 15.37B hrs | Japanese: 7.06B hrs | Hindi: 0.92B hrs.

Release Strategy

Over 65% of major releases premiere late in the week to leverage weekend viewing windows.

Thursday & Friday releases generate the highest initial 3-day viewership.

🛠️ Tools & Technologies

Programming Language: Python 3.8+

Data Manipulation: pandas, numpy

Data Visualization: matplotlib, seaborn

Environment: Jupyter Notebook

Presentation Deck: PowerPoint (python-pptx)

📁 Repository Structure

├── Netflix_Content_Analysis.ipynb    # Main Jupyter Notebook containing data cleaning, EDA, and plots
├── netflix_content.csv               # Raw and processed Netflix engagement dataset
├── requirements.txt                  # List of Python dependencies
├── presentation/
│   └──Netflix_Content_Analysis_.pptx # 15-slide dark-themed executive presentation
└── README.md                         # Project documentation


🚀 Getting Started

Prerequisites

Ensure you have Python 3.8+ installed on your system.
Ensure you have korean supported font installed on your system.


Installation

Clone the repository:

git clone https://github.com/amarjeet-AIML/Netflix-Content-Analysis.git
cd Netflix-Content-Analysis


Install required packages:

pip install -r requirements.txt


Launch the Jupyter Notebook:


Open content_recommend.ipynb to run the data analysis workflow.

👤 Author

Data Analytics Project

GitHub: @amarjeet-AIML

Dataset Source: Publicly available Netflix viewing dataset on Kaggle.
