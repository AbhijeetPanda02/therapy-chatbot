# 🧠 Therapy Chatbot
## 🌟 Overview
Therapy Chatbot is a Python-based mental health assistant that provides empathetic, supportive, and calming responses to users. It combines large language models (LLM) with text-to-speech (TTS) to deliver a human-like conversational experience, helping users manage stress, anxiety, or negative emotions.

---

## 🚀 Features

- 💬 **LLM-powered conversation :** Dynamic responses using OpenRouter LLM (gpt-4 or gpt-3.5-turbo)
- 😌 **Mood-aware guidance :** Adjusts tone based on user input
- 🔊 **Human-like voice output :** Uses pyttsx3 offline TTS or ElevenLabs for neural TTS
- 🛡️ **Safe and supportive :** Offers coping strategies and encourages professional help when necessary
- 🔄 **Interactive chat loop :** Remembers context for continuous, personalized conversations

---

## 📦 Installation
Install required Python packages:

#### pip install openai pyttsx3 textblob

## 🔑 API Key

- OpenRouter API key (required)

## ⚙️ How to Use
1. Clone or download the repository.

2. Open Therapy_chatbot.ipynb in Jupyter Notebook or Google Colab.

3. Set your OpenRouter API key:

    import openai
    
    client = openai.OpenAI(
        api_key="YOUR_API_KEY",
    base_url="https://openrouter.ai/api/v1")

4. Run all cells sequentially.

5. Start chatting with the bot:
You: Hi

Bot: Hello! How are you feeling today?

6. Type exit to quit the conversation.
## ⚡ Optional Enhancements
📱 Replace pyttsx3 with ElevenLabs TTS for a more natural, human-like voice.

📦 Add a GUI or web interface using Streamlit, Flask, or Gradio.

🧪 Expand coping strategies and mood tracking for a richer therapy experience.

## ⚠️ Safety Note
This chatbot is intended for **supportive conversation only**. It does not **replace professional mental health care**. Users experiencing severe distress should **contact licensed professionals or helplines**.

## 👨‍💻 Author
**Abhijeet Panda**

GitHub: [https://github.com/AbhijeetPanda02?tab=repositories]

