# Vibe_Matcher_by_Vishwanathpradapsingh
This project is a simple AI-based vibe matching system that recommends similar users based on their interests and personality traits. It uses TF-IDF vectorization and cosine similarity to compute closeness between users and suggest the top matches.
 Features

✔ Creates a sample dataset of users
✔ Converts text into vectors using TF-IDF
✔ Computes similarity using cosine similarity
✔ Recommends top-3 similar users
✔ Logs similarity scores for evaluation
✔ Simple & beginner-friendly implementation

Tech Used

Python

Pandas

Scikit-Learn (TF-IDF + Cosine Similarity)

Google Colab

How It Works

User interests + personality → text features

TF-IDF transforms text into numeric vectors

Cosine similarity finds closest matches

System prints recommendations for any user

Example Output
Top matches for Aarav:
Riya — Similarity: 0.72
Dev — Similarity: 0.59
Kabir — Similarity: 0.55

Evaluation

Average similarity score is calculated

Matches above 0.7 are considered “Good”

Improvements (Future Work)

Replace TF-IDF with OpenAI Embeddings

Add Pinecone or FAISS for fast vector search

Add more real-world dataset & UI

Why this project?

This mini recommendation demo shows how AI can understand human “vibes” and find smart matches using text similarity.
It reflects how real recommendation engines in social media & dating apps work.

Author

G Vishwanath Pradap Singh
AI/ML & Full-Stack enthusiast
