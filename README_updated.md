AI-Powered Support Ticket Triage (Python + ML Project)

This project simulates a real-world AI workflow for a support team by combining rule-based logic, machine learning, and data visualization in Python. Built entirely in Google Colab and shared as a complete, reproducible project.

Project Overview

This support ticket triage system:
- Automatically categorizes support tickets using both rule-based logic and machine learning
- Scores urgency with custom priority detection
- Generates AI-style auto-replies based on predicted issue type
- Visualizes support trends over time
- Trains and evaluates a real ML model on ticket text

Technologies Used

- Python 3
- pandas
- scikit-learn (Multinomial Naive Bayes)
- matplotlib
- TfidfVectorizer (for NLP)
- Google Colab

Features

| Feature | Method |
|--------|--------|
| Auto-Categorization | Rule-based logic + ML model |
| Auto-Priority Scoring | Rule-based logic |
| AI Replies | Template-based generation |
| Visualizations | Time series, bar chart, pie chart |
| Machine Learning | Trained classifier with accuracy & classification report |
| Reproducible Code | Full Colab notebook included |

Visualizations

- Ticket volume over time
- Ticket count by category
- Priority distribution (percent breakdown)

Machine Learning Workflow

- **Input:** Ticket text
- **Model:** Naive Bayes using TF-IDF
- **Output:** Predicted support category
- **Metrics:** Accuracy score and classification report

Files

- `ai_ticket_project_final.xlsx`: Final dataset (original + AI + ML)
- `support_ticket_ai_project.ipynb`: Full notebook with all logic, charts, and model training
- `README.md`: This file

Learning Reflection

This project was built from scratch to practice:
- Python data analysis
- Natural language classification
- Simulating real support team workflows with AI
- Training and validating a text classifier
- Visualizing trends and results

View the Full Notebook

[support_ticket_ai_project.ipynb](./support_ticket_ai_project.ipynb)

How to Run

1. Open the notebook in Google Colab or VS Code
2. Run cells from top to bottom
3. Customize or expand with your own ticket data or model enhancements

Credits

Built step-by-step to support AI skill-building and portfolio growth.
