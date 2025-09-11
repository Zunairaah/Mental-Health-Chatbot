
# 🧠💬 Mental Health FAQ Chatbot

This project is a simple **chatbot** built using **Python, NLTK, and scikit-learn** that provides answers to frequently asked questions about **mental health**. The chatbot uses **text preprocessing, TF-IDF vectorization, and cosine similarity** to generate responses from a given dataset. The main aim of the project is to provide quick, informative responses and encourage awareness around mental health in an interactive way.

---

## 🔍 Project Workflow

* 📂 **Dataset**

  * The chatbot is trained on a dataset of **Mental Health FAQs** stored in a CSV file.
  * The questions and answers are preprocessed for tokenization and normalization.

* 🧹 **Text Preprocessing**

  * Lowercasing text for consistency
  * Tokenization of words and sentences
  * Lemmatization using WordNet
  * Removal of punctuation and stopwords

* 🗨️ **Greeting System**

  * A small function that detects greetings like *hi, hello, hey*
  * Responds with random friendly replies

* 🤖 **Response Generation**

  * Uses **TF-IDF Vectorizer** to convert text into numerical form
  * Computes **cosine similarity** between user input and dataset responses
  * Returns the most relevant answer or an error message if nothing matches

* 🎯 **Conversation Flow**

  * Starts with a welcome message
  * Keeps interacting until the user types **“bye”**
  * Handles polite endings like *thanks* or *thank you*

---

## 🛠️ Tools & Libraries

* Python 🐍
* NumPy
* NLTK (tokenization, lemmatization)
* scikit-learn (TF-IDF, cosine similarity)
* Google Colab / Jupyter Notebook

---

## 📈 Example Interaction

```
BOT: My name is Zunaira. Let's have a conversation! Also, if you want to exit any time, just type Bye!
User: hi
BOT: hi there
User: what is personality disorder?
BOT: obsessive-compulsive personality disorder is one of the most common personality disorders.
User: bye
BOT: Goodbye! Take care <3
```

---

## 🧠 Outcome

This chatbot demonstrates how **rule-based NLP with TF-IDF similarity** can be used to build a simple Q\&A system. While it is not as advanced as deep learning models, it provides a good foundation for understanding how chatbots process natural language and match user queries to existing data.

---

⚡ **Future Improvements**

* Use **deep learning models (Transformers / BERT)** for more context-aware responses
* Add **GUI or Web App deployment** for accessibility
* Expand the dataset with more FAQs for better coverage

