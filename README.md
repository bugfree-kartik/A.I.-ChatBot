🩺 AI-Health-Chatbot — End-to-End ML + NLP Healthcare Assistant

AI-Health-Chatbot is an end-to-end Python project that transforms free-text symptom descriptions into disease likelihoods with confidence scores, wrapped in an interactive, doctor-style chatbot experience.

It demonstrates the full ML lifecycle:
Data prep → NLP feature engineering → Model training (Random Forest) → Conversational reasoning → Actionable health advice


🚀 Features

🗣️ Natural-language intake: Parses messy symptom text (e.g., “fever, bad cough at night, slight chest pain”).

📊 Structured reasoning: Maps extracted symptoms into model-ready features; asks targeted follow-up questions to reduce uncertainty.

🤖 Probabilistic prediction: Trained RandomForestClassifier outputs top-k candidate conditions with predict_proba confidence scores.

💡 Actionable output: Provides precautions, general health tips, and a motivational closing.

🛠️ Tech Stack

Language: Python 🐍

Libraries: scikit-learn, pandas, NLP preprocessing tools

Model: Random Forest Classifier 🌲

Interface: Interactive chatbot (command-line based)

📌 Project Workflow

Data Preparation → Cleaning and preprocessing symptom datasets

Feature Engineering → NLP-based symptom extraction and encoding

Model Training → Random Forest classification with probability scores

Chatbot Flow → Interactive follow-up Q&A for better accuracy

Output Generation → Predicted conditions, precautions, and health tips



![chatBot](https://github.com/user-attachments/assets/9e67a239-c887-40e1-a5cb-23313abe1e64)
