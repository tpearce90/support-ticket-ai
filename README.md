
# 🧠 AI-Powered Support Ticket Triage (Python + ML Project)

This project simulates a real-world AI workflow for a support team by combining rule-based logic, machine learning, and data visualization in Python.

---

## 📌 Project Overview

This support ticket triage system can:
- Automatically categorize incoming support tickets using both keyword logic and machine learning
- Score urgency with rule-based priority detection
- Generate auto-responses
- Visualize trends with charts
- Export results to Excel

---

## 🧰 Technologies Used

- Python 3
- pandas
- scikit-learn (Naive Bayes)
- matplotlib
- TfidfVectorizer (for NLP)
- Google Colab

---

## 🔍 Features

| Feature | Method |
|--------|--------|
| Auto-Categorization | Rule-based logic (keywords) + ML model |
| Auto-Priority Scoring | Rule-based logic |
| AI Replies | Template-based responses |
| Data Visualization | Charts (line, bar, pie) |
| ML Model | Trained using Naive Bayes on ticket text |

---

## 🧪 Machine Learning Details

- **Input:** Ticket text
- **Output:** Predicted category
- **Model:** Multinomial Naive Bayes
- **Vectorizer:** TF-IDF
- **Accuracy:** Measured on test set (see notebook)

---

## 📊 Visualizations

- Ticket volume over time (line chart)
- Tickets by category (bar chart)
- Ticket priority distribution (pie chart)

---

## 📁 Files

- `ai_ticket_project_final.xlsx`: Combined results (original + AI + ML)
- `support_ai_notebook.ipynb`: Full Colab notebook
- `README.md`: This documentation

---

## 📚 Learning Reflection

This project was built from scratch as a hands-on way to learn:
- Python data analysis
- Text processing and classification
- AI simulation logic
- Real-world portfolio project development

---

## 🚀 How to Run

1. Open the notebook in Google Colab
2. Upload the Excel file or use your own
3. Run each cell to retrain, analyze, and visualize
4. Customize or expand the ML model if desired

---

## 🤝 Credits

Built step-by-step as a guided project to support Python and AI learning from scratch.

