# SteamNoodles Feedback Agents — Piranavan

**University:** University of Moratuwa 
**Year:** 2nd Year

---

## 📌 Project Summary

This project implements a **multi-agent AI framework** for **SteamNoodles**, a restaurant chain, to automate and personalize customer feedback analysis using modern AI techniques.

- **Agent 1: Feedback Response Agent**  
  Analyzes individual customer reviews, determines sentiment using **Groq LLM**, and generates a short, polite, and context-aware automated reply.

- **Agent 2: Sentiment Visualization Agent**  
  Generates dynamic sentiment trend plots over user-specified date ranges, showing counts of positive, neutral, and negative reviews per day.

The agents use a **Kaggle restaurant review dataset** for demonstration.

---

## 📂 Dataset

- Source: [Kaggle Restaurant Reviews Dataset]([https://www.kaggle.com](https://www.kaggle.com/datasets/farukalam/yelp-restaurant-reviews))  
- After preprocessing, important columns are:
  - `Review_Text` — Customer feedback text  
  - `Sentiment` — Sentiment label (Positive, Neutral, Negative)  
  - `Date` — Datetime of review submission
  - `Rating` — Custommer Rating  



---

## ⚙️ Setup Instructions

1. **Clone this repository**
   ```bash
   git clone https://github.com/Piranavan25/Restaurant-review-agent.git
   cd Restaurant-review-agent
