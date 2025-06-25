# News Bias Detection Using Word2Vec and Logistic Regression

## 📄 Project Overview  
This project explores the use of **Word2Vec** embeddings model to evaluate how effectively a neural network-based text representation can distinguish the political tendencies of different news agencies based on news headlines.

## 🗂️ Data Collection  
The dataset was **manually collected** and curated by me. I selected news headlines covering the **same events**, reported by four different news agencies — **two from each side of the political spectrum**. This comparative dataset consists of **10 news events**, providing a controlled setup to observe how language framing differs across outlets.

## 🛠️ Methodology  
- Headlines were preprocessed using **NLTK** for tokenization and text cleaning  
- A **Word2Vec** model was applied to generate vector representations of the headlines, capturing underlying semantic patterns  
- Headlines from the same event across different outlets were compared to evaluate the model's ability to detect framing bias  

## 🎯 Objectives  
The goal is to assess:  
- How effectively **Word2Vec embeddings** capture subtle linguistic patterns in news headlines  
- The extent to which a **logistic regression model**, built on these embeddings, can distinguish the political leaning of a news agency  

## 📊 Conclusion  
This project demonstrates the potential of word embedding techniques for bias detection in news reporting and provides insights into how headline framing may reflect political tendencies across media outlets.

---
