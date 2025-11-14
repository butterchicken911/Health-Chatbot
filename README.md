# Health-Chatbot
An AI Chatbot for Health Care - MY AI Digital Assignment
This chatbot was created using Google Collaborator 

Health Chatbot (Q&A and Symptom Diagnostics)
This project features a basic health chatbot with dual capabilities: answering general health questions (Q&A) and providing preliminary diagnostic suggestions based on user-described symptoms. It uses NLP techniques for Q&A retrieval and machine learning for symptom-to-disease mapping.

Key Features:
Q&A System: Utilizes TF-IDF and Nearest Neighbors for health information retrieval.
Symptom Diagnostics: Employs MultiLabelBinarizer and LogisticRegression to suggest diseases from symptoms.
Smart Fallback: A refined relevance threshold ensures accurate answers for relevant queries and generic responses for irrelevant ones, enhancing user experience.
Medical Disclaimers: All diagnostic outputs include clear disclaimers, emphasizing they are not medical advice.
Technologies:
Python, Pandas, Scikit-learn (TfidfVectorizer, NearestNeighbors, MultiLabelBinarizer, LogisticRegression).

How to Run:
Clone the repository, open the .ipynb file in Google Colab, and run all cells sequentially to interact with the chatbot.

