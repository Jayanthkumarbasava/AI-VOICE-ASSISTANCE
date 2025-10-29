# AI-VOICE-ASSISTANCE
🗣️ Voice Assistant — Python Project

A lightweight text-based voice assistant built using Python, capable of responding to user commands through speech synthesis. It can greet you, tell the time/date, open websites, perform Google searches, and more — all in your terminal.

![Preview Screenshot](https://github.com/Jayanthkumarbasava/AI-VOICE-ASSISTANCE/blob/main/Screenshot%202025-10-29%20161503.png?raw=true) 

🚀 Features

✅ Speech Output – Converts text to speech using pyttsx3.
✅ Smart Greetings – Greets you based on the current time of day.
✅ Command Recognition – Understands various simple commands like:

“What’s the time?”

“What’s today’s date?”

“Open YouTube”

“Search for Python tutorials”
✅ Web Integration – Opens Google or YouTube in your default browser.
✅ Interactive Search – Prompts user input to perform live Google searches.
✅ Exit Gracefully – Ends session with a polite goodbye message.

🧠 Tech Stack
Component	Description
Language	Python 3.x
Libraries Used	pyttsx3, datetime, webbrowser, os, time
Platform	Works on Windows, macOS, and Linux (with Python 3)
⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/voice-assistant.git
cd voice-assistant

2️⃣ Install Dependencies
pip install pyttsx3


(Other modules like datetime, webbrowser, and os are built into Python.)

3️⃣ Run the Assistant
python "voice ass.py"

💡 How It Works

Initialization: The program greets you based on system time.

Command Input: You type a command (e.g., “open google”).

Processing: The command is analyzed and matched against known tasks.

Execution: The assistant performs the action and responds via voice output.

🧩 Example Usage
Enter your command (type 'exit' to quit): what time is it  
> The current time is 04:25 PM  

Enter your command: open youtube  
> Opening YouTube.  

Enter your command: exit  
> Goodbye! Have a great day.

🛠️ Future Enhancements

🔹 Add speech recognition (e.g., via speech_recognition library)
🔹 Integrate AI-based chat responses using OpenAI or Gemini APIs
🔹 Enable custom command training
🔹 Add GUI interface using Tkinter or PyQt

📁 Project Structure
voice-assistant/
│
├── voice ass.py      # Main script
├── README.md         # Project documentation
└── requirements.txt  # Dependencies (optional)

👨‍💻 Author

Jayanth
📧 [Your Email or LinkedIn]
💻 Passionate about Python automation and AI projects

🪪 License

This project is licensed under the MIT License – you’re free to use, modify, and distribute with attribution.
