---
layout: home
title: "James Ndarila"
author_profile: true
---

## 🚀 Welcome!

Hi, I’m **James Ndarila** — an ICT specialist and Data & AI enthusiast passionate about analytics, machine learning, and building intelligent solutions.

I am currently advancing my skills through the **Cyber Shujaa Data & AI Program**, focusing on real-world machine learning, NLP, and data-driven systems.

📄 [Download My Resume (PDF)](/assets/files/assets/James-Ndarila-CV.pdf)

---

## 🔧 Featured Projects

### Customer Churn Prediction
Machine learning model to predict customer churn using classification algorithms.  
🔗 https://github.com/Ndarila/customer-churn-prediction

---

### Netflix Data Wrangling & EDA
Exploratory data analysis on Netflix dataset to identify content trends and insights.  
🔗 https://github.com/Ndarila/netflix-data-wrangling-eda

---

### Deep Learning Projects
Neural network models for classification and prediction tasks using deep learning.  
🔗 https://github.com/Ndarila/deep-learning-projects

---

### NLP with Transformers
Text classification and NLP tasks using BERT and HuggingFace Transformers.  
🔗 https://github.com/Ndarila/nlp-transformers

---

### BERT Sentence Similarity
Semantic similarity model using Sentence-BERT embeddings and cosine similarity.  
🔗 https://github.com/Ndarila/bert-sentence-similarity

---

### MLOps Projects
Machine learning pipelines, automation, and deployment workflows.  
🔗 https://github.com/Ndarila/mlops-projects

---

### Data Scraping Project
Web scraping automation and structured data extraction from websites.  
🔗 https://github.com/Ndarila/data-scraping-project

---

## 📝 Latest Posts

{% if site.posts.size > 0 %}
{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url | relative_url }}) – {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
{% else %}
_No blog posts yet. Check back soon!_
{% endif %}