Title: Building Multi-Label Text Classifiers Of Scholarly Research Articles Using Deep Learning 

📌 Overview
This project focuses on automatically classifying arXiv research paper abstracts into multiple relevant subject categories. Unlike traditional classification, this task allows a single abstract to belong to multiple classes simultaneously (multi-label classification). Both conventional machine learning and deep learning models were explored.

🧠 Key Features
Multi-label classification on real-world academic data.
Preprocessing: tokenization, stopword removal, lemmatization.
Feature extraction using TF-IDF and Word2Vec.
Traditional models: Logistic Regression, Naive Bayes.
Deep learning models: MLP and LSTM using Word2Vec embeddings.
Evaluation using metrics: Precision, Recall, F1-score, and Confusion Matrix.
Final predictions on new research abstracts.

🗂 Project Structure
multi-label-text-classification/
├── data/             # Sample CSV dataset
├── code.ipynb        # Jupyter source file
├── requirements.txt  # Required Python packages
├── README.md         # This file
├── LICENSE           # Open source license
└── .gitignore        # Files to exclude from version control

📊 Results
Traditional models like Logistic Regression and Naive Bayes performed well with TF-IDF features.
Enhanced model performance using label-wise training and binarization.
Deep learning models (MLP & LSTM) using Word2Vec embeddings gave better context understanding.
Confusion matrices and metrics show improved precision and recall for top categories.

🔮 Future Scope
Experiment with transformer models like BERT for better contextual understanding.
Use full-text data instead of only abstracts.
Improve label balancing with augmentation or resampling techniques.
Deploy as an API or web app for real-time abstract classification.

📄 License
This project is licensed under the MIT License.
