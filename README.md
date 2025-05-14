 Mental Health AI Chatbot

Talk-Ease is a simple, interactive AI-powered chatbot designed to offer mental wellness support through natural conversations. Built using Flask, HTML/CSS/JavaScript, and powered by Meta's LLaMA model (via Ollama), it also integrates TensorFlow for optional emotion analysis.

---

## 🧠 Features

- Real-time chat interface (HTML/CSS/JavaScript)  
- AI-driven responses using Meta’s LLaMA via Ollama  
- Python Flask backend to manage API routing  
- Optional emotion detection via TensorFlow  
- Lightweight and easy to run locally  

---

## 🔧 Tech Stack

- Frontend: HTML, CSS, JavaScript  
- Backend: Flask (Python)  
- AI Model: LLaMA (via Ollama)  
- Emotion Detection (Optional): TensorFlow  

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/venkatesh0029/Talk-Ease chatbot.git
cd luma-chatbot

---

### 2. Set Up Python Environment
Install the necessary packages:

bash
Copy
Edit
pip install flask flask-cors tensorflow

---

### 3. Install and Run Ollama
Install Ollama from https://ollama.com

Then download and run the LLaMA model:

bash
Copy
Edit
ollama pull llama3
ollama run llama3
(Keep this running in a separate terminal while chatting.)

---

### 4. Run the Flask Backend
bash
Copy
Edit
python app.py
5. Open the Frontend
Open index.html in your browser.

---

You’re ready to chat with Luma!

🗂️ Project Structure
bash
Copy
Edit
luma-chatbot/
├── app.py           # Flask backend
├── index.html       # Chat UI
├── style.css        # Styling
├── script.js        # Frontend logic
└── README.md        # Documentation
💡 Optional: Add Emotion Detection
You can plug in a TensorFlow model for detecting sentiment or emotional tone from user messages to adapt chatbot responses accordingly.

📄 License
This project is licensed under the MIT License.

