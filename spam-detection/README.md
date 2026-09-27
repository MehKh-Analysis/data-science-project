#  Spam Detection

Classifying text messages as **spam (1)** or **not spam (0)** from their content. Spam is a common channel for fraud and unwanted promotions, so reliable filtering matters for security.

## Approach

- **Text features:** TF-IDF vectorization of message content
- **Models:**
  - **Naive Bayes (MultinomialNB):** fast, lightweight, and interpretable; a classic fit for word-frequency features
  - **Logistic Regression:** a strong baseline for binary classification


<img width="845" height="1190" alt="download" src="https://github.com/user-attachments/assets/f7c53689-c732-4f1b-8b59-e8d11b376908" />


**Key takeaway:** Naive Bayes performed best and is the recommended model. *[add one line on why, e.g. precision on spam]*

## Files

- `spam_detection.ipynb`: full analysis
- `requirements.txt`: dependencies
