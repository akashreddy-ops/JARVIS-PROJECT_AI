# JARVIS-PROJECT_AI

# 🤖 JARVIS - Voice Controlled Personal Assistant

> "Hello, I'm JARVIS. How can I help you today?"  
Welcome to my Python-based virtual assistant project inspired by Tony Stark’s JARVIS! Built from scratch using Python, NLP, and voice recognition libraries, this assistant can interact with you via voice commands, manage tasks, open applications, and provide intelligent responses.

---

## 🧠 What is JARVIS?

JARVIS (Just A Rather Very Intelligent System) is a **voice-controlled AI assistant** designed to make your desktop life easier. It can:

- Greet you personally
- Open/close apps like Chrome, Notepad, Calculator, etc.
- Read your daily class schedule
- Answer custom queries
- Learn responses via training data (`intents.json`)
- Respond intelligently using trained NLP models

---

## 🛠️ Tech Stack

| Tech/Library       | Purpose                                |
|--------------------|-----------------------------------------|
| **Python**         | Core programming language               |
| **SpeechRecognition** | For capturing and converting voice to text |
| **pyttsx3**        | For voice output (text-to-speech)       |
| **NLTK / scikit-learn** | Natural Language Processing and classification |
| **TensorFlow / Keras** | Neural network model training         |
| **VS Code**        | Code Editor                            |

---

## 📁 Project Structure

📂 JARVIS/
│
├── intents.json # Training data for the model (user patterns & responses)
├── chat_model.h5 # Trained Keras model
├── label_encoder.pkl # Encoded class labels
├── tokenizer.pkl # Fitted tokenizer for text input
├── model_train.py # Trains the model using intents.json
├── main.py # Main assistant logic (speech input, schedule, app handling)
├── model_test.py # Interface for testing voice commands
├── venv/ # Python virtual environment


---

## 🚀 Features

- 🔊 **Voice Activation** – Talk to JARVIS, and it listens!
- 🧾 **Personalized Daily Schedule** – Custom day-wise class schedule
- 💻 **App Management** – Open/Close system apps via command
- 🧠 **AI-Powered Responses** – Trained on intent patterns using a custom dataset
- 📚 **Easy to Train** – Just update the `intents.json` and retrain!

---

## 🧪 How to Run Locally

1. **Clone the repository**  
```bash
               


