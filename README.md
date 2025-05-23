# 🤖 Intent-Based Chatbot with Streamlit

An intuitive chatbot that understands user input using Natural Language Processing (NLP) and responds with contextually appropriate answers. Built with Python, Streamlit, NLTK, and Scikit-learn, this project demonstrates how to classify intents and generate intelligent responses.

---

## 🚀 Live Preview

Not applicable for web hosting.  
💡 To try the chatbot, run the `app.py` script locally using Streamlit.

```bash
streamlit run app.py
```

---

## 📸 Screenshots


![Chatbot Screenshot 1](https://raw.githubusercontent.com/shIVam18004/P4-Implementation-of-Chatbot-using-NLP-main/main/Chat_1.png)  
![Chatbot Screenshot 2](https://raw.githubusercontent.com/shIVam18004/P4-Implementation-of-Chatbot-using-NLP-main/main/Chat_2.png)  
![Chatbot Screenshot 3](https://raw.githubusercontent.com/shIVam18004/P4-Implementation-of-Chatbot-using-NLP-main/main/Chat_3.png)

---

## 🛠️ Features

- 🧠 **Classifies user input into predefined intents**  
- 📚 **Displays intelligent responses from `intents.json`**  
- 💬 **Logs all conversations into `chat_log.csv`**  
- 🧪 **Training done via Logistic Regression & TF-IDF vectorizer**  
- 🎛️ **Streamlit GUI for interaction and history viewing**  
- 📝 **About section with system overview**

---

## 🧩 Project Structure

```
.
├── app.py              # Main application (Streamlit UI)
├── intents.json        # Predefined intents, patterns, and responses
├── chat_log.csv        # Logs user-bot conversations
├── chatbot.ipynb       # Notebook for experimentation
├── hello.txt           # Miscellaneous or note file
├── requirements.txt    # Project dependencies
├── venv/               # Virtual environment folder
```

---

## 📂 Tech Stack

| Technology      | Purpose                                                                 |
|------------------|-------------------------------------------------------------------------|
| 🐍 Python         | Core programming language                                               |
| 🧠 NLTK           | Tokenization, text processing                                           |
| 📊 scikit-learn   | TF-IDF vectorizer + Logistic Regression classifier                      |
| 🌐 Streamlit      | Web interface for chatbot                                               |
| 📄 JSON           | Storing intents with patterns and responses                             |
| 📈 CSV            | Logging chat history for later reference                                |

---

## 📋 How to Run

1. **Clone the repository**  
   ```bash
   git clone https://github.com/shIVam18004/P4-Implementation-of-Chatbot-using-NLP-main.git
   cd P4-Implementation-of-Chatbot-using-NLP-main
   ```

2. **Create a virtual environment & activate it**  
   ```bash
   python -m venv venv
   source venv/bin/activate     # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the chatbot**  
   ```bash
   streamlit run app.py
   ```

---

## 📜 Intent Dataset: `intents.json`

Each intent consists of:
```json
{
  "tag": "enchanted_snow",
  "patterns": ["Walking in enchanted snow", "The beauty of magical snowfall"],
  "responses": [
    "Enchanted snow is a mythical phenomenon...",
    "Snow is a meteorological event..."
  ]
}
```

- **tag**: Unique name of the intent  
- **patterns**: Example user messages  
- **responses**: Random bot replies for that intent  

---

## 🧠 What I Learned

💡 This project helped reinforce the following concepts:

- ✅ How to preprocess natural language with NLTK  
- ✅ Building intent classifiers using machine learning  
- ✅ Visualizing chatbot responses using Streamlit  
- ✅ Handling real-time inputs and saving history in CSV  
- ✅ Designing conversational JSON structures

---

## 🚀 Possible Enhancements

- ✨ Add deep learning support using LSTM or BERT  
- 🌐 Integrate with an API for dynamic intent generation  
- 🧵 Context tracking and session memory  
- 🎨 Advanced UI using frontend tools like React or ChatGPT-style design

---

## 📃 License

MIT License — feel free to use, modify, and distribute for educational or personal use.

---

## 🙋 About

An NLP-based chatbot built to explore conversational AI and create engaging text-based interactions with real-time responses using machine learning models and intuitive UI.
