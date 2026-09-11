# 🤖 CodeAlpha FAQ Chatbot

## CodeAlpha Artificial Intelligence Internship — Task 2

An AI-powered **FAQ Chatbot** developed as part of the CodeAlpha Artificial Intelligence Internship.

The chatbot accepts questions from users and finds the most relevant answer from a predefined collection of Frequently Asked Questions (FAQs) using **Natural Language Processing (NLP)** techniques.

---

## 🎯 Project Objective

The objective of this project is to develop a chatbot that can:

* Accept questions from users.
* Preprocess the user's question.
* Compare the question with predefined FAQs.
* Find the most similar FAQ.
* Return the corresponding answer.
* Provide a fallback response when no suitable answer is found.

---

## ✨ Features

* 🤖 Interactive FAQ chatbot interface
* 📝 Natural language question input
* 🔤 Text preprocessing
* 📊 TF-IDF text vectorization
* 📐 Cosine similarity for question matching
* 💬 Chat-style conversation interface
* ❌ Fallback response for unknown questions
* 🗑️ Clear chat functionality
* 🌐 Runs in Google Colab

---

## 🧠 How It Works

The chatbot follows these steps:

```text
User Question
      ↓
Text Preprocessing
      ↓
TF-IDF Vectorization
      ↓
Cosine Similarity
      ↓
Compare with FAQ Questions
      ↓
Find Most Similar FAQ
      ↓
Return Answer
```

### 1. User Input

The user enters a question through the chatbot interface.

Example:

```text
How many projects do I have to finish?
```

### 2. Text Preprocessing

The question is converted to lowercase and unnecessary c
