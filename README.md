# 🧠 AI Policy Feedback Intelligence System

An AI-powered web application that analyzes public consultation feedback and transforms unstructured comments into structured, decision-ready insights.

---

## 🚀 Overview

Government portals receive thousands of public comments on draft policies.  
Manual analysis is slow, error-prone, and not scalable.

This system automates:
- Sentiment analysis
- Confidence scoring
- Feedback prioritization
- Insight generation
- Report creation

---

## 🎯 Key Features

- 🔍 Sentiment Classification (Positive / Neutral / Negative)
- 📊 Interactive Dashboard with analytics
- ⚠️ Confidence-based "Needs Review" flagging
- 🧾 AI-generated summaries
- 📁 CSV Export & PDF Report Generation
- 📌 Topic-wise sentiment breakdown
- 🔐 User authentication & history tracking

---

## ⚙️ Tech Stack

### Frontend
- HTML, CSS, JavaScript

### Backend
- Python (Flask)

### AI / ML
- TF-IDF + Logistic Regression (Baseline)
- RoBERTa Transformer (Fine-tuned)
- Hugging Face Transformers
- PyTorch

### Data Processing
- Pandas, NumPy, NLTK

### Visualization
- Matplotlib, Plotly, WordCloud

### Reporting
- PDF generation (ReportLab / FPDF)

---

## 🧠 AI Model Approach

### 1. Baseline Model
- TF-IDF + Logistic Regression
- Used for initial benchmarking and pipeline validation

### 2. Advanced Model
- Fine-tuned RoBERTa Transformer
- Handles contextual understanding of policy text
- Achieves high accuracy (~98%)

---

## 🔄 How It Works

1. User uploads CSV file with comments
2. System processes and analyzes text
3. Sentiment and confidence scores are generated
4. Low-confidence comments are flagged for review
5. Dashboard displays insights
6. Reports can be downloaded (PDF/CSV)

---

## 📊 Dashboard Highlights

- Sentiment distribution
- Confidence analysis
- Word cloud visualization
- Topic-wise breakdown
- Searchable comment table
- Needs-review panel

---

## 🏗️ System Architecture

Frontend → Flask Backend → AI Model → Analytics → Dashboard & Reports

---

## 📈 Results

- Handles real-world noisy data
- Scalable for large datasets
- Supports human-in-the-loop decision making

---

## 🔮 Future Scope

- Multilingual sentiment analysis
- Topic modeling (advanced clustering)
- Real-time data processing
- Integration with government portals
- Explainable AI (XAI)

---

## 📌 Conclusion

This project is not just a sentiment classifier.  
It is a complete **AI-driven decision support system** for policy analysis.

---

## 🤝 Contribution

Feel free to fork, contribute, or suggest improvements.

---

## 📧 Contact

Akash Kumar  
Final Year B.Tech CSE Student
