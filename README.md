Here’s the translated README for your **Sentiment Analysis of Blu Bank App on Play Store using Machine Learning** project:

---

# 📊 Sentiment Analysis of Blu Bank App on Play Store Using Machine Learning

## 📝 Project Description
This project aims to analyze user sentiment toward the **Blu Bank** app on **Google Play Store** using **Machine Learning** techniques. By leveraging **Natural Language Processing (NLP)**, this project classifies user reviews as **positive, negative, or neutral**, providing valuable insights for app developers to enhance user experience.

## 🚀 Key Features
- **Web Scraping**: Collect user review data from Google Play Store.
- **Data Preprocessing**: Clean, tokenize, and normalize text for analysis.
- **Machine Learning Models**: Utilize algorithms like **Naïve Bayes, Support Vector Machine (SVM), or BERT** for sentiment classification.
- **Model Evaluation**: Measure accuracy using metrics such as **precision, recall, and F1-score**.

## 🔧 Technologies Used
- **Python** (pandas, numpy, scikit-learn, TensorFlow)
- **Natural Language Processing (NLP)**
- **Google Colab** for model experimentation
- **Flask** (optional) for deploying sentiment prediction API

## 📂 Directory Structure
```
├── data/                 # Dataset of Blu Bank app reviews
├── notebooks/            # Jupyter Notebook for exploration and model training
├── src/                  # Main code for preprocessing and modeling
├── models/               # Trained machine learning models
├── app/                  # Flask-based API (optional)
├── README.md             # Project documentation
```

## 🔎 How to Use
1. Clone this repository:
   ```bash
   git clone [https://github.com/iseptianto/Sentiment-Analysis-of-BLU-Bank-Application-in-Playstore-with-Machine-Learning-Approach]
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run preprocessing and model training:
   ```bash
   python src/train_model.py
   ```
4. Use the trained model for sentiment prediction:
   ```bash
   python src/predict.py "This app is very helpful!"
   ```

## 📊 Results & Analysis
Here’s the updated **Results & Analysis** section incorporating your accuracy details:  

---

## 📊 Results & Analysis  
The sentiment analysis model was evaluated on user reviews of the **Blu Bank** app, testing multiple machine learning algorithms. The results show that **Logistic Regression** performed best in sentiment classification:  

| Model                | Accuracy Test |
|----------------------|--------------|
| **Logistic Regression** | **79.37%** |
| **Random Forest**     | **75.89%** |
| **Naïve Bayes**       | **73.48%** |
| **Decision Tree**     | **68.80%** |

- **Logistic Regression** provided the highest accuracy, making it a reliable choice for classifying sentiment.  
- **Random Forest** also performed well but was slightly less accurate than Logistic Regression.  
- **Naïve Bayes** showed reasonable results but struggled with complex sentence structures.  
- **Decision Tree** had the lowest accuracy, indicating potential overfitting or misclassification challenges.  

Most user reviews were **positive**, though some expressed concerns regarding **app performance and data security**. These insights can help developers improve future updates.  

## 📌 References
- [User Sentiment Analysis of Blu BCA App](https://ejournal.itn.ac.id/index.php/jati/article/view/9216)
- [Mobile Banking Sentiment Analysis Using SVM](https://j-ptiik.ub.ac.id/index.php/j-ptiik/article/download/5792/2748/)
- [Sentiment Analysis with BERT](https://www.academia.edu/123106731/ANALISIS_SENTIMEN_TERHADAP_ULASAN_APLIKASI_BLU_BY_BCA_MENGGUNAKAN_METODE_BIDIRECTIONAL_ENCODER_REPRESENTATIONS_FROM_TRANSFORMERS_BERT_)

---

Feel free to update this README to better match your project implementation. Let me know if you need any improvements! 🚀
