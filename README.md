
# AI-Powered Support Ticket Triage (Python and Machine Learning Project)

This project simulates a real-world AI workflow for a support team by combining rule-based logic, machine learning, and data visualization in Python. It was developed entirely in Google Colab as a complete, reproducible project.

## Project Overview

This support ticket triage system:
- Automatically categorizes support tickets using both rule-based logic and machine learning
- Scores urgency using custom priority detection
- Generates auto-replies based on predicted issue type
- Visualizes support trends
- Trains and evaluates a machine learning model on support ticket text

## Technologies Used

- Python 3
- pandas
- scikit-learn (Multinomial Naive Bayes)
- matplotlib
- TfidfVectorizer
- Google Colab

## Features

| Feature | Method |
|--------|--------|
| Auto-Categorization | Rule-based logic and ML model |
| Priority Scoring | Rule-based logic |
| AI Replies | Template-based generation |
| Visualizations | Time series, bar chart, pie chart |
| Machine Learning | Text classification model with accuracy and classification report |
| Reproducible Code | Full Google Colab notebook included |

## Visualizations

- Ticket volume over time
- Ticket count by category
- Priority distribution

## Machine Learning Workflow

- Input: Ticket text
- Model: Naive Bayes with TF-IDF vectorization
- Output: Predicted category
- Evaluation: Accuracy score and classification report

## Files

- ai_ticket_project_final.xlsx: Final dataset with AI-enhanced features
- support_ticket_ai_project.ipynb: Complete notebook with all logic, charts, and model training
- README.md: Project description

## Learning Reflection

This project was created to practice:
- Python for data analysis
- Natural language classification
- Simulating support workflows with AI
- Training and evaluating a machine learning model
- Visualizing support ticket trends

## View the Notebook

support_ticket_ai_project.ipynb contains all the logic, model training steps, and visualizations used in this project.

## How to Run

1. Open the notebook in Google Colab or any Python environment
2. Run the cells from top to bottom
3. Modify or extend with additional data or logic as needed
