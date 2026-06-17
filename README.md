# 🤖 Chatbot Using Widgets

An interactive chatbot built using Python and NLTK that responds to user queries through pattern matching and a widget-based interface. The chatbot can answer basic greetings and provide information about Artificial Intelligence (AI), Machine Learning (ML), and Deep Learning (DL).

---

## 📌 Project Overview

This project demonstrates the fundamentals of chatbot development using Python. The chatbot uses predefined patterns and responses to interact with users and provide instant answers to common questions.

The project was developed as a learning exercise to understand:

- Natural Language Processing (NLP)
- Pattern Matching
- Conversational AI
- Python Programming
- Widget-Based User Interfaces

---

## 🚀 Features

✅ Greeting Detection

- Hi
- Hello
- Hey
- Helo
- Hlo

✅ AI Concepts

- What is AI?
- What is Machine Learning?
- What is Deep Learning?

✅ Interactive Chat Interface

✅ Pattern Matching Using Regular Expressions

✅ Beginner-Friendly Code Structure

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Core Programming Language |
| NLTK | Chatbot Framework |
| Regex | Pattern Matching |
| Google Colab | Development Environment |
| Jupyter Widgets | Interactive UI |

---

## 📂 Project Structure

```text
Chatbot_Using_widgets/
│
├── Chatbot_rb.ipynb
├── README.md
└── requirements.txt
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Ashishkumar217/Chatbot_Using_widgets.git
```

### 2. Navigate to Project Folder

```bash
cd Chatbot_Using_widgets
```

### 3. Install Required Libraries

```bash
pip install nltk ipywidgets
```

---

## ▶️ Running the Project

### Using Google Colab

1. Open the notebook in Google Colab.
2. Run all cells.
3. Enter your message in the chatbot interface.
4. Receive instant responses.

### Using Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
Chatbot_rb.ipynb
```

Run all cells.

---

## 💡 Sample Conversation

### User

```text
hello
```

### Bot

```text
Hello! How are you Buddy
```

---

### User

```text
what is ai
```

### Bot

```text
AI (Artificial Intelligence) is the ability of a computer or machine
to perform tasks that normally require human intelligence.
```

---

### User

```text
what is ml
```

### Bot

```text
ML (Machine Learning) is a branch of AI that enables computers
to learn from data without being explicitly programmed.
```

---

### User

```text
what is deep learning
```

### Bot

```text
Deep Learning (DL) is a subset of Machine Learning that uses
artificial neural networks with many layers.
```

---

## 🧠 How It Works

The chatbot uses:

1. Regular Expression Patterns
2. Predefined Responses
3. NLTK Chat Module

Example:

```python
pairs = [
    [r"hi|hello|hey", ["Hello! How are you Buddy"]],
    [r"what is ai", ["AI stands for Artificial Intelligence"]],
]
```

When a user enters a message, the chatbot:

1. Matches the input with a pattern.
2. Selects the corresponding response.
3. Displays the answer.

---

## 🔮 Future Improvements

- Voice Input Support
- Text-to-Speech Responses
- More AI Knowledge Base
- Integration with Gemini/OpenAI APIs
- Sentiment Analysis
- GUI Application using Tkinter
- Web Deployment using Flask or Streamlit

---

## 🎯 Learning Outcomes

Through this project, I learned:

- Python Programming
- NLP Basics
- Chatbot Development
- Pattern Matching Techniques
- Interactive Widgets
- GitHub Project Management

---

## 👨‍💻 Author

**Ashish Kumar**

GitHub: https://github.com/Ashishkumar217

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.
