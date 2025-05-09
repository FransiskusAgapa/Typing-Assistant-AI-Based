# AI-based Typing Assistant

## What is this?

This is a simple Python project that predicts the **next word** as a user types. It's powered by a small language model (GPT2-small) and shows how natural language processing (NLP) works in real-time typing applications. As a fun stretch goal, the assistant can also suggest an emoji based on the **sentiment** of your typed sentence.

---

## Why this app?

Typing assistants are becoming increasingly common in modern tools (like Gmail, Docs, etc). This project shows how you can build a simple version using real machine learning models. It's a great way to demonstrate your knowledge of:

* NLP (Natural Language Processing)
* Machine Learning basics
* Python programming
* Software design and structuring small AI systems

---

## Tech Stack

| Component            | Technology Used                            | Reason                         |
| -------------------- | ------------------------------------------ | ------------------------------ |
| Language Model       | GPT2-small (via Hugging Face Transformers) | Lightweight and fast           |
| Programming Language | Python                                     | Easy to learn and widely used  |
| Sentiment Analysis   | DistilBERT (optional stretch goal)         | For emoji suggestion           |
| Interface (optional) | Terminal-based or Streamlit (for web demo) | Simple to use or show visually |

---

## How it works

1. **Typing Simulation**
   As you type into the program, it takes your last few words and tries to predict what word comes next.

2. **Word Prediction**
   A small pretrained GPT2 model is used to generate likely next words. The top prediction (or top 3 suggestions) are shown.

3. **(Optional) Sentiment Emoji**
   After a sentence is complete, the assistant checks the overall mood using a sentiment model and suggests a relevant emoji.

---

## How to Use

1. Clone the project repository (or download the files).
2. Install the required libraries using `pip install -r requirements.txt`.
3. Run the typing assistant using `python main.py`.
4. (Optional) Run `python train_model.py` if you want to fine-tune your own version of GPT2.
5. (Optional) Run `python sentiment_emoji.py` to test sentiment-to-emoji suggestions.

---

## Possible Future Improvements

* Add word autocomplete (not just next-word suggestion).
* Display multiple suggestions in a dropdown UI.
* Add a browser-based front-end using Streamlit or React.
* Allow users to switch models or train on their own data.
* Support multiple languages (for international typing assistance).
* Make the app mobile-friendly with voice input support.
