🎙️ Voice Assistant using Python
This project is a desktop-based voice assistant that can understand and respond to user commands using speech recognition. It automates various tasks such as opening websites, searching Wikipedia, playing music, telling jokes, and more.

---

📁 Project Files
File Name	          	Description
main.py		        🧠 Main script that runs the voice assistant logic
Pip installer.py	⚙️ Script to install all required Python libraries
Voice.iml		      📦 PyCharm project configuration file

---

🔧 Setup Instructions
1. Clone the repository:
git clone https://github.com/YOUR-USERNAME/voice-assistant-python.git
cd voice-assistant-python
2. Run the pip installer script (optional method):
python "Pip installer.py"
Or manually install packages:
pip install wolframalpha wikipedia ecapture twilio beautifulsoup4 winshell pyjokes feedparser clint SpeechRecognition pyttsx3 pyaudio setuptools
3. Run the assistant:
python main.py

---

📝 Notes
- Ensure your microphone is connected and working.
- Replace placeholder values in the code (e.g., email/password, API keys).
- This project is Windows-specific due to use of `win32com`, `winshell`, etc.

---

📜 License
This project is created by Garisha Grover as a minor academic project in Summer Training.
