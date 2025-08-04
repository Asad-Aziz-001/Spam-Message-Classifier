# **📦 Project Summary: Spam Message Classifier (ML Internship)**


# **🎯 Objective:**

Build a machine learning model that classifies SMS messages as Spam or Not Spam (Ham) using text preprocessing, vectorization, and classification techniques.

# **✅ Dataset Used:**

Source: /kaggle/input/sms-spam-collection-dataset/spam.csv

Format: CSV with two columns:

v1: Label (ham or spam)

v2: Message text

# **🧹 Text Preprocessing:**

Applied the following cleaning steps:

Lowercasing text

Removing URLs, punctuation, special characters

Removing stopwords (using NLTK)

Tokenizing and joining cleaned tokens

# **📊 Feature Extraction:**

Used TF-IDF Vectorizer to convert text into numerical features.

# **🔀 Modeling:**

Model Used: Multinomial Naive Bayes (simple & effective for text classification)

Train/Test Split: 80% training, 20% testing

Performance:

Accuracy: ~94%

Evaluation: Accuracy score, classification report, confusion matrix

5 predictions displayed with message + predicted label

# **📈 Visualizations:**

Top Spam Words: Bar chart using seaborn showing most frequent spam terms.

Correlation Heatmap:

Initially showed only label

Enhanced with message_length and word_count to analyze numeric relationships.

# **🖥️ Bonus – CLI Classifier:**

Implemented a Command Line Interface for real-time message prediction:

User enters any message

Model returns "Spam" or "Not Spam" instantly

# **💾 Model Saving:**

Saved trained model as spam_model.pkl

Saved TF-IDF vectorizer as vectorizer.pkl using joblib

# **🔧 Technologies Used:**

pandas, scikit-learn, nltk, matplotlib, seaborn, joblib


# **📝 Conclusion**

| Component              | Description                          |
| ---------------------- | ------------------------------------ |
| 📊 Accuracy            | e.g., 94% or above                   |
| 📷 Confusion Matrix    | Shown in output                      |
| 📄 5 Predictions       | Printed to console                   |
| 💾 Model Saved         | `spam_model.pkl`, `vectorizer.pkl`   |
| 🔍 CLI Interface       | Bonus: Predict new messages manually |
| 📈 Spam Word Bar Chart | Bonus: Use `seaborn`                 |
