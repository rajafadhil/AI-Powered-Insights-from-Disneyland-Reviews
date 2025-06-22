# 🏰 AI-Powered Insights from Disneyland Reviews

A data analysis project using **IBM Granite LLM** to extract sentiment-based insights from user reviews across three Disneyland parks: California, Paris, and Hong Kong. This project combines exploratory data analysis (EDA) with advanced NLP through large language models (LLMs) to summarize reviews and uncover patterns in visitor experiences.

---

## 📌 Project Overview

This project aims to extract insights from thousands of Disneyland reviews sourced from TripAdvisor. By combining data visualization with AI-based text summarization, we seek to:

- Understand visitor satisfaction and pain points
- Compare user sentiment across Disneyland California, Paris, and Hong Kong
- Showcase the value of LLMs (IBM Granite) in real-world review analysis

---

## 🗂️ Dataset

The dataset is sourced from [Kaggle - Disneyland Reviews](https://www.kaggle.com/datasets/mateenahmedzai/disneyland-reviews) and includes:

- `Review_Text`: Review content
- `Rating`: Score (1–5)
- `Branch`: Park location (California, Paris, Hong Kong)
- `Reviewer_Location`: Country of origin
- `Year_Visited`: Visit year

---

## 📊 Exploratory Data Analysis (EDA)

1. **Rating Distribution**  
   Majority of reviews have a 5-star rating, indicating high satisfaction.

2. **Review Volume by Park**  
   California has the highest number of reviews, followed by Paris and Hong Kong.

3. **Reviewer Location**  
   Top reviewers come from the US and UK, reflecting travel and proximity trends.

4. **Keyword Themes**  
   - Positive reviews: `ride`, `kid`, `fun`, `fast pass`
   - Negative reviews: `queue`, `staff`, `wait`, `price`

5. **Time Trends**  
   Review activity peaked around 2015 and gradually declined, possibly influenced by global events or park developments.

---

## 🤖 AI Support Explanation

### How AI is Used

The IBM Granite LLM (Large Language Model) was used for:

1. **Summarization**  
   Generating concise summaries of reviews per park.

2. **Insight Extraction**  
   Identifying top 3 recurring praises and complaints per location.

3. **(Optional) Sentiment Classification**  
   Future work may include full-scale sentiment classification using LLM or ML models.

### Why Use LLMs

- Handles unstructured text effectively
- Understands context, sarcasm, and nuance
- Saves time vs manual or rule-based sentiment tagging

### Example Prompt

```text
From the following reviews, identify:
1. The top 3 most frequent complaints
2. The top 3 most frequent praises
```
---

## 🧠 Insight & Findings
### Disneyland California
Praises:
- Exceptional customer service
- Magical atmosphere and iconic rides
- FastPass system improves experience

Complaints:
- Expensive food and merchandise
- Long wait times for rides
- Overcrowding during peak seasons

### Disneyland Paris
Praises:
- Well-organized and clean park
- Immersive Disney-themed atmosphere
- FastPass feature appreciated

Complaints:
- Long queues and ride closures
- High prices, even outside the park
- Some staff perceived as indifferent

### Disneyland Hong Kong
Praises:
- Magical and family-friendly environment
- Easy access via public transport, great shows
- Shorter lines during weekdays

Complaints:
- Smaller size than other Disney parks
- Mixed quality of food relative to price
- Long queues during peak hours

---

## ✅ Conclusion & Recommendation
Conclusion
- Overall sentiment is positive across all parks.
- FastPass, customer service, and theming are consistently appreciated.
- Common challenges include price, queue time, and seasonal overcrowding.
- Each park has distinct strengths and operational weaknesses.

Recommendations
For Disneyland Management:
- Improve Queue Management
   - Enhance FastPass or introduce app-based queueing
- Reassess Pricing Strategy
   - Offer budget-friendly dining or bundling options
- Staff Training & Consistency
   - Emphasize hospitality, particularly in Paris and Hong Kong

For Visitors:
- Visit Off-Season
   - November and weekdays offer better comfort
- Use FastPass Strategically
   - Prioritize popular attractions and book in advance
- Plan & Budget Accordingly
   - Expect premium prices for food and experiences

---

## 🧰 Tools & Technologies
- Python (Pandas, Seaborn, Matplotlib, WordCloud)
- IBM Granite LLM via Replicate API
- Google Colab Notebook
- GitHub

---

## 🗂️ Slide PDF
[Link to Slide](https://drive.google.com/file/d/1X6baeWproK4T0cpuLteRliT5mPiw2kTG/view?usp=sharing)
