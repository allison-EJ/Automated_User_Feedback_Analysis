# Automated_User_Feedback_Analysis

## Overview
This repository contains the complete workflow and resources for my Bachelor’s Thesis: an automated framework for analyzing mobile app user feedback.  

The project applies **Natural Language Processing (NLP)** methods, specifically **BERTopic** for topic modeling and **VADER** for sentiment analysis, to systematically process and interpret user reviews from mobile applications.  

The goal is to generate prioritized, actionable insights that can guide product management decisions.

---

## Features
- **Data Preprocessing**: Cleans and structures raw review data for analysis.
- **Topic Modeling**: Uses BERTopic with reduced topics (`nr_topics=50`) for interpretable clustering of feedback.
- **Sentiment Analysis**: Implements VADER to capture sentiment nuances in user reviews.
- **Prioritization**: Ranks topics by importance to highlight key areas for product improvement.
- **Visualization**: Includes figures for topic distribution, sentiment breakdown, and prioritized insights.

---

## Repository Structure
```
Automated_User_Feedback_Analysis/
│
├── Code_Folder/                     # Jupyter notebooks and Python scripts
├── Csv_Data_Folder/                 # Processed CSV datasets
├── Figures_Folder/                  # Charts and visualizations
└── README.md                        # Project overview
```

---

## Getting Started

### 1️ Clone the repository
```
git clone https://github.com/allison-EJ/Automated_User_Feedback_Analysis.git
cd Automated_User_Feedback_Analysis
```

### 2️ Install dependencies
This project uses **Python 3.9+** and requires the following libraries:
```
pip install pandas numpy matplotlib seaborn spacy bertopic nltk
```

### 3️ For sentiment analysis
```
python -m nltk.downloader vader_lexicon
```

---

## Data Availability
Due to file size limits on GitHub, some CSV files are tracked using **Git LFS**.  
Ensure Git LFS is installed to download large datasets:

```
git lfs install
```

All datasets are anonymized and sourced from publicly available mobile app review data.
