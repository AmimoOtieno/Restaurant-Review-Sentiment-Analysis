# Restaurant-Review-Sentiment-Analysis
This project uses Natural Language Processing (NLP) and Machine Learning to classify restaurant reviews as **positive or negative**.

## Objective

Customer reviews are valuable for understanding satisfaction and improving services.  
This project builds a model that automatically predicts sentiment from text reviews.

---

## Techniques Used

- Text preprocessing (cleaning, tokenization, stopword removal, lemmatization)
- Bag of Words (CountVectorizer)
- Machine Learning (Naive Bayes)
- Model explainability using SHAP

---

## Dataset

- Contains restaurant reviews labeled as:
  - `1` → Positive
  - `0` → Negative

---

## Workflow

1. Data Cleaning
2. Text Preprocessing
3. Feature Extraction (Bag of Words)
4. Model Training (Naive Bayes)
5. Model Evaluation
6. Explainability with SHAP

---

## Installation

```bash
git clone https://github.com/yourusername/restaurant-review-sentiment-analysis.git
cd restaurant-review-sentiment-analysis
pip install -r requirements.txt
```
## Results
*Successfully classifies restaurant reviews*

<img width="634" height="397" alt="image" src="https://github.com/user-attachments/assets/774314d1-08c5-4a75-9d0d-b85185c4cf00" />

*Provides insights into important words influencing predictions using SHAP*
<img width="760" height="940" alt="image" src="https://github.com/user-attachments/assets/7e76d838-79d0-44f4-a48b-2a4885842a92" />

The SHAP summary plot shows how individual words influence the model’s sentiment predictions. Words positioned on the right push predictions toward positive sentiment, while those on the left push toward negative sentiment.

The model strongly associates words like “great,” “good,” “delicious,” and “love” with positive reviews, while words such as “bad,” “terrible,” “wait,” and “bland” drive negative predictions.

Additionally, the spread of points for each word indicates that their impact can vary depending on context, but overall, the model captures clear and intuitive patterns in customer feedback.

*What words show up the most in customer feedback*
<img width="992" height="517" alt="image" src="https://github.com/user-attachments/assets/2de50abc-714a-44d5-8f8a-515246c03a62" />


*Example Insights*

Words like "great", "amazing" → Positive sentiment
<img width="985" height="542" alt="image" src="https://github.com/user-attachments/assets/87297486-8d77-4f80-a4c0-aa66fcd0267c" />


Words like "bad", "worst" → Negative sentiment
<img width="998" height="546" alt="image" src="https://github.com/user-attachments/assets/2cdd4c36-f363-4493-aab5-93ab9573ec67" />


## Dependencies
pandas

numpy

nltk

scikit-learn

matplotlib

shap

## Future Improvements
Try deep learning models (LSTM, BERT)

Deploy as a web app

Add real-time predictions

👤 Author
Hellen Otieno
https://www.linkedin.com/in/hellen-otieno/
hellenamimo72@gmail.com
