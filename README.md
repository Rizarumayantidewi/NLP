<img width="640" height="547" alt="image" src="https://github.com/user-attachments/assets/a4e7d21a-7301-47f5-a80c-1e0a0e52d562" />## 📊 Sentiment Analysis of Indonesia VAT 12% Policy on Instagram

## 📌 Description
This project analyzes public sentiment toward Indonesia’s planned Value-Added Tax (VAT) increase to 12% by 2025. The study focuses on Instagram comments from Narasi Newsroom posts, using text mining and machine learning approaches to understand public opinion and engagement patterns.

A total of 1,634 comments were collected via the Instagram Graph API and processed through several NLP stages including data cleaning, tokenization, and sentiment classification.

## 🎯 Objectives
- To analyze public sentiment regarding the VAT 12% policy
- To compare sentiment classification methods:
    -> Lexicon-based (VADER)
    -> Machine Learning (Logistic Regression & Random Forest)
    -> K-Fold Cross-Validation
- To identify dominant sentiment trends and public concerns
- To evaluate model performance in sentiment classification

## 🛠 Tools & Technologies
- Programming: Python
- Libraries: Pandas, NumPy, Scikit-learn, NLTK, VADER Sentiment
- Machine Learning: Logistic Regression, Random Forest
- Visualization: Matplotlib, Seaborn
- Data Source: Instagram Graph API

## 📊 Results
- Total Data: 1,634 comments
- Sentiment Distribution:
  -> Positive: 629
  -> Neutral: 598
  ->  Negative: 407
- Model Performance
  -> K-Fold Cross-Validation Accuracy: 69%
  -> Random Forest Accuracy: 71%
  -> Logistic Regression Accuracy: 75%

## 📷 Visualization
Workflow
<img width="436" height="606" alt="Fig 1  Workflow" src="https://github.com/user-attachments/assets/7dee3df5-cdbf-43ea-941a-e42006f8e89a" />

Sentiment Count Leicon-based
<img width="410" height="62" alt="Fig 2  Sentiment Count Lexicon-based" src="https://github.com/user-attachments/assets/6eea7cff-d071-47ba-9b77-c45584944cd2" />

Top 10 Words
<img width="140" height="204" alt="Fig 3  Top 10 Words" src="https://github.com/user-attachments/assets/6b16fa66-6668-4c52-9ab4-6b7bf847a575" />

📊 Bar chart distribusi sentimen
<img width="695" height="547" alt="Fig 8  Sentiment Analysis Results" src="https://github.com/user-attachments/assets/ef1577fb-ad97-44c4-a482-0dcaf5802b9b" />

☁️ Wordcloud komentar
<img width="1019" height="519" alt="Fig 9  Word Cloud" src="https://github.com/user-attachments/assets/eb727afc-9ac0-4195-b114-00ccaa154f34" />

📉 Confusion matrix model <img width="640" height="547" alt="image" src="https://github.com/user-attachments/assets/9cd84523-2ade-498f-978d-19e78b69bec6" />

📈 Perbandingan performa model
<img width="357" height="231" alt="image" src="https://github.com/user-attachments/assets/6fe9097a-939a-48b1-99d7-c5c708dca11f" />

<img width="312" height="124" alt="image" src="https://github.com/user-attachments/assets/31f17774-4965-41df-8b42-b0b9a5b8c6c6" />

## 🚀 Insights
- Sentimen netral mendominasi, menunjukkan masyarakat masih dalam tahap observasi terhadap kebijakan
- Sentimen negatif banyak menyoroti dampak ekonomi pada masyarakat menengah ke bawah
- Sentimen positif cenderung mendukung kebijakan untuk peningkatan pendapatan negara
- Model Random Forest cenderung memberikan performa lebih stabil dibanding Naive Bayes dalam klasifikasi teks kompleks

## 📎 Future Work
- Menggunakan Deep Learning (LSTM / BERT) untuk peningkatan akurasi
- Menambah dataset dari platform lain (Twitter, TikTok)
- Topic modeling untuk analisis isu spesifik
