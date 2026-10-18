# 🤖 NewsBot Intelligence System
**Course:** ITAI 2373 — Natural Language Processing (Midterm Project)  
**Student:** Edwin Andres Marquez Rueda  
**Dataset:** BBC News Classification (Kaggle - 2,225 articles, 5 categories)  
**Repository URL:** https://github.com/eandresmarquez12/ITAI2373-NewsBot-Midterm-  

---

## 📌 Project Overview
NewsBot is a comprehensive, end-to-end NLP intelligence pipeline developed to automate news article classification, entity extraction, sentiment analysis, and linguistic pattern exploration across Modules 1 to 8. Built using Python, spaCy, NLTK, and scikit-learn in Google Colab.

## 🛠️ Pipeline Modules Covered
1. **Module 1: Real-World Context & Business Case** — Newsroom monitoring and decision-support automation.
2. **Module 2: Advanced Text Preprocessing** — Normalization, HTML/URL removal, tokenization, stop-word filtering, and WordNet lemmatization.
3. **Module 3: TF-IDF Feature Extraction** — N-gram feature mapping, sparsity analysis, and category term scoring.
4. **Module 4: POS Pattern Analysis** — Grammatical profiling across categories using spaCy.
5. **Module 5: Syntax Parsing** — Dependency trees, noun chunking, and subject-verb-object triple extraction.
6. **Module 6: Sentiment Analysis** — VADER lexicon tone scoring and compound distribution analysis.
7. **Module 7: Multi-Class Text Classification** — Model comparison (Multinomial Naive Bayes, Logistic Regression, Linear SVM) using leak-free Pipelines.
8. **Module 8: Named Entity Recognition (NER)** — Entity extraction and breakdown (`PERSON`, `ORG`, `GPE`, `DATE`, `MONEY`).

## 📊 Summary of Results
- **Best Classifier:** Logistic Regression / Linear SVM (~97% Accuracy, ~0.97 Macro F1-Score).
- **Dataset Scale:** 2,225 BBC news articles across 5 primary categories (Business, Entertainment, Politics, Sport, Tech).

---

## 📁 Repository Structure
```text
ITAI2373-NewsBot-Midterm-/
├── .gitignore
├── README.md
└── NewsBot_Intelligence_System_Final_Working_Template.ipynb
