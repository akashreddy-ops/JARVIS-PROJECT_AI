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

1.     **Clone the repository**  

       git clone https://github.com/yourusername/jarvis-voice-assistant.git
       cd jarvis-voice-assistant

2.      python -m venv venv
        venv\Scripts\activate    # On Windows

3.      pip install -r requirements.txt

4.       python model_train.py
5.     python model_test.py



| Command            | Response / Action                            |
| ------------------ | -------------------------------------------- |
| “open chrome”      | Launches Google Chrome                       |
| “open notepad”     | Launches Notepad                             |
| “today’s schedule” | Speaks out your current day’s class schedule |
| “hi” or “hello”    | Friendly reply from JARVIS                   |
| “open whatsapp”    | Opens WhatsApp Desktop (if installed)        |


📷 Screenshots


<img width="1919" height="1079" alt="Screenshot 2025-07-19 231057" src="https://github.com/user-attachments/assets/02827976-a940-400d-bc2c-35e8e8b1c8e0" />
<img width="1908" height="1032" alt="Screenshot 2025-07-19 232840" src="https://github.com/user-attachments/assets/13703f60-eeb3-42c7-93a1-3bde873e98b3" />
<img width="1914" height="1021" alt="Screenshot 2025-07-19 233528" src="https://github.com/user-attachments/assets/d08a60fd-ab59-484e-869c-a298b21ca98a" />
<img width="1919" height="1079" alt="Screenshot 2025-07-20 105015" src="https://github.com/user-attachments/assets/a5aa5a9e-cc89-4d7c-89c8-533b19968a8d" />
<img width="1913" height="1076" alt="Screenshot 2025-07-20 105033" src="https://github.com/user-attachments/assets/75869167-3421-4333-ba53-d31cd98813f9" />
<img width="1919" height="1079" alt="Screenshot 2025-07-20 105043" src="https://github.com/user-attachments/assets/e63cfde2-99e1-4f05-be90-eb687009d624" />

💡 What I Learned

 - Implementing voice recognition and text-to-speech in Python
 - Structuring and training a basic NLP model using intents.json
 - Creating a modular assistant that can be extended with new commands
 - Automating desktop workflows

🌱 Future Improvements
 - Integrate voice wake-word (e.g., “Hey JARVIS”)
 - Add GUI for non-terminal users
 - Connect with APIs (Weather, Calendar, Email)
 - Add personalized reminders and alarms

📬 Contact
 - If you liked this project or have suggestions, feel free to connect with me:
   Akash Reddy Danapana

   🔗 LinkedIn(https://www.linkedin.com/in/akash-reddy-a761b3321/overlay/contact-info/)


   📫 Email: danapanaakashreddy999@gmail.com

⭐ Feedback
   - If you found this project useful or interesting, don't forget to star ⭐ this repository and share it!
It motivates me to learn and build more exciting projects like this.





