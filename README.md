Consumer Reviews of Amazon Products – NLP Assignment
📌 Project Overview

- This project implements an end-to-end Natural Language Processing (NLP) pipeline to analyze Amazon product reviews and generate actionable insights for product managers.

- The project focuses on automated sentiment analysis and key issue detection from customer feedback on products like Kindle, Fire TV, Echo, and other Amazon-branded devices.

🎯 Stakeholders & Pain Points
Stakeholder: Amazon Product Managers

Challenges addressed:

- Overwhelmed by Review Volume – Manually reviewing thousands of customer comments is inefficient.

- Lack of Granular Feedback – Star ratings don’t reveal why customers feel a certain way.

- Slow Issue Detection – Emerging product issues go unnoticed until widespread.

- Inefficient Resource Allocation – Development efforts aren’t always aligned with customer needs.


🎯 Goals of the Project

This project aims to:

- Automate sentiment classification (Positive, Negative, Neutral) of product reviews.

- Identify recurring themes & issues (e.g., battery life, screen quality, customer service).

- Provide actionable insights for proactive decision-making.

- Enable scalable monitoring for continuous product improvement.


📂 Dataset
Source: Consumer Reviews of Amazon Products (Kaggle)

Size: ~34,000 reviews

Fields Used:

- reviews.text – Customer review text

- reviews.rating – Rating (1–5 stars)


🛠️ Project Workflow

- Data Loading & Exploration

- Dataset overview, class distribution, and sample reviews.

- Preprocessing

- Lowercasing, punctuation removal, tokenization.

- Stopword removal, stemming/lemmatization.

- Feature Engineering

- Bag-of-Words, TF-IDF, n-grams, and embeddings.

- Handling Class Imbalance

- Techniques like RandomOverSampler & class weighting.

- Modeling & Evaluation

- Logistic Regression for sentiment classification.

- Metrics: Accuracy, Precision, Recall, F1-score.

- Visualization

- Word clouds for positive/negative reviews.

- Sentiment distribution plots & heatmaps.

- Insights & Recommendations

- Identifying recurring themes in negative reviews.

- Actionable suggestions for stakeholders.


📊 Key Visualizations

- Sentiment Distribution Graph

- Word Clouds for positive & negative reviews

- Aspect-Sentiment Heatmaps


📈 Results

- Baseline sentiment classifier using Logistic Regression.

- Improved interpretability via visualization & theme extraction.

- Framework for scaling to other Amazon product lines.


🚀 Future Scope

- Advanced models (BERT, RoBERTa) for better sentiment detection.

- Topic modeling (LDA) for automatic issue categorization.

- Deployment as a dashboard for real-time monitoring.

📧 Author
Abdul Aleem
