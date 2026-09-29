# 🚗 AI-Based Automotive Review and Customer Sentiment Analytics

An AI/ML-based system for analyzing automotive customer reviews and identifying sentiment at the aspect level using Natural Language Processing (NLP) and BERT.

The system analyzes a vehicle review, identifies specific automotive aspects, and predicts whether the sentiment associated with each aspect is Positive, Negative, or Neutral.

---

## 📌 Project Overview

Customer reviews contain valuable information about different aspects of a vehicle, such as battery performance, engine, mileage, safety, comfort, service, infotainment, and price.

Traditional sentiment analysis usually determines whether an entire review is positive or negative. This project goes further by performing **Aspect-Level Sentiment Analysis (ALSA)**.

### Example

**Input Review:**

> "The battery range is excellent, but the charging time is too long."

### Expected Analysis

| Aspect | Sentiment |
|---|---|
| Battery Range | Positive |
| Charging Time | Negative |

This allows vehicle manufacturers, dealers, and analysts to understand customer opinions about individual vehicle features.

---

## 🎯 Objectives

- Analyze automotive customer reviews using NLP.
- Extract important vehicle-related aspects.
- Perform aspect-level sentiment classification.
- Classify sentiment into:
  - Positive
  - Neutral
  - Negative
- Use BERT for contextual sentiment understanding.
- Provide an easy-to-use prediction system for new automotive reviews.
- Support data-driven analysis of customer feedback.

---

## 🧠 Technologies Used

- Python
- Natural Language Processing (NLP)
- BERT
- Hugging Face Transformers
- PyTorch
- Scikit-learn
- Pandas
- NumPy
- Google Colab
- GitHub

---

## 🏗️ System Architecture

         Automotive Reviews
                         │
                         ▼
                 Text Preprocessing
                         │
                         ▼
                Aspect Identification
                         │
                         ▼
                 BERT Tokenization
                         │
                         ▼
                  BERT Model
                         │
                         ▼
             Sentiment Classification
                         │
             ┌───────────┼───────────┐
             ▼           ▼           ▼
          Positive     Neutral     Negative
             │           │           │
             └───────────┼───────────┘
                         ▼
              Aspect-Level Results


MuSe-CarASTE Dataset — GitHub
```text
        
