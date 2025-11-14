# Health-Chatbot
An AI Chatbot for Health Care - MY AI Digital Assignment
This chatbot was created using Google Collaborator 

Project Title: Health Chatbot with Q&A and Symptom-Based Diagnostics
Overview
This project develops a basic health chatbot capable of answering general health-related questions and providing preliminary diagnostic suggestions based on user-described symptoms. It integrates Natural Language Processing (NLP) techniques for question-answering and machine learning for symptom-to-disease mapping, demonstrating a proof-of-concept for an interactive health assistant.

Features
Dual Functionality: Seamlessly switches between a Question-Answering (Q&A) system and a symptom-based diagnostic predictor.
Knowledge Base: Utilizes two primary datasets:
A Medical Q&A Dataset for general health inquiries.
A Symptom-Disease Mapping Dataset for diagnostic predictions.
Q&A Retrieval: Employs TF-IDF (Term Frequency-Inverse Document Frequency) for text vectorization and Nearest Neighbors for efficient similarity-based response retrieval.
Symptom-Based Diagnostics: Uses MultiLabelBinarizer to preprocess symptom inputs and a LogisticRegression model to predict potential diseases from identified symptoms.
Intelligent Fallback: Features a refined relevance threshold that ensures accurate Q&A responses for relevant queries while gracefully directing irrelevant or ambiguous questions to a generic 'no information' message, preventing misleading answers.
Medical Disclaimers: All diagnostic suggestions are accompanied by clear medical disclaimers, emphasizing that the chatbot's output is not a substitute for professional medical advice.
Interactive Interface: A simple command-line interface allows users to easily interact with the chatbot.
Technologies Used

Python: The core programming language.
Pandas: For data manipulation and management of Q&A and symptom-disease datasets.
Scikit-learn: For machine learning models, including TfidfVectorizer, NearestNeighbors, MultiLabelBinarizer, and LogisticRegression.
io and re modules: For in-memory data handling and regular expression-based symptom extraction.

How to Run
Clone the Repository:
git clone https://github.com/butterchicken911/Health-Chatbot.git
cd butterchicken911/Health-Chatbot
Open in Google Colab: Upload the Untitled1.ipynb file to Google Colab or open it directly via GitHub (File -> Open notebook -> GitHub tab).
Run All Cells: Execute all cells in the notebook sequentially.
Interact: Once the final cell containing the interactive chatbot loop is executed, you can start asking questions or describing symptoms.
Type quit or exit to end the conversation.

Future Enhancements (Ideas)
Expand the Q&A and symptom-disease datasets with more diverse and larger real-world data.
Implement more sophisticated NLP models for symptom extraction and intent recognition (e.g., using transformer-based models).
Integrate a confidence score for diagnostic predictions.
Develop a more user-friendly graphical interface.
Explore advanced dialogue management techniques for multi-turn conversations.
