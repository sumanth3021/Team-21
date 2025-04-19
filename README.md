🔍 Abstract
This project classifies Quora questions using Natural Language Processing (NLP) to detect duplicate or insincere questions. It aims to improve content moderation and enhance search results on platforms like Quora by identifying harmful or misleading content using NLP techniques and machine learning models.

🧠 Introduction
Online Q&A platforms often face issues with spam or inappropriate questions. Manual moderation is time-consuming. This project leverages NLP and machine learning to automate the detection of such questions, improving platform quality and user experience.

🛠️ Technologies Used
Languages: Python, HTML, CSS

Frameworks: Flask (for web deployment)

Libraries:

NLP: NLTK, spaCy

ML/DL: Scikit-learn, TensorFlow, Keras

Data Handling: Pandas, NumPy

Tools: Google Colab / Jupyter Notebook

⚙️ Methodology
Data Collection

Dataset contains Quora questions labeled as sincere or insincere.

Publicly available for NLP research.

Data Preprocessing

Tokenization, stop-word removal, stemming, lemmatization.

Text vectorization using TF-IDF and Word2Vec/GloVe embeddings.

Model Development

Logistic Regression / Random Forest for classification.

Prediction & Deployment

The trained model predicts question sincerity.

Can be deployed via Flask as a web application.

📊 Results
The model demonstrates high accuracy in classifying questions.

Enables faster, automated content moderation.

✅ Conclusion
This NLP-based system provides an effective way to detect and filter out insincere questions. It helps improve user trust and platform quality with minimal manual effort.
