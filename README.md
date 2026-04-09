# 🗣️ Voice-Activated Personal Assistant
**Your Intelligent, Voice-Powered Helper**

This project showcases skills in Python programming, API integration, and building voice-enabled applications. From setting reminders to fetching real-time weather updates, this assistant is your productivity companion.

## 🌟 Key Features
- 🎙️ **Voice Recognition**: Understands and processes user commands through speech recognition.
- 🔊 **Text-to-Speech Responses**: Delivers clear, human-like responses using the pyttsx3 library.
- 📰 **Smart Task Execution**: Perform tasks like setting reminders 📅, checking the weather 🌤️, and reading the latest news 📰.
- 🌐 **Real-Time Data Integration**: Fetch real-time updates (e.g., weather and news) via APIs.
- ⚙️ **Customizable Framework**: Easily extend functionality to suit specific needs.

## 🛠️ Technologies Used
| Component            | Description                                    | Library/API              |
|----------------------|------------------------------------------------|--------------------------|
| 🎙️ Speech Recognition| Recognize voice commands                      | speechrecognition         |
| 🔊 Text-to-Speech     | Convert text responses into spoken output      | pyttsx3                   |
| 🌤️ Weather Updates   | Fetch real-time weather for any location      | OpenWeatherMap API        |
| 📰 News Headlines     | Provide the latest news updates               | NewsAPI                   |



## ⚙️ Setup and Installation
Follow these steps to set up the assistant:

1. **Install Dependencies**  
  To install the required libraries for this project, run the following commands:

   ```bash
   pip install speechrecognition
   pip install pyttsx3
   pip install requests
   pip install pytz
  
2. **Configure APIs**
  - Obtain an API key for OpenWeatherMap for weather updates.
  - (Optional) Set up NewsAPI for accessing the latest news.
  - Store the API keys securely in the script or a .env file.
  - Refer to the .env.example file for configuration.
3. **Run the Assistant**
    Start the assistant using the following command:
    ```bash
    python assistant.py
4. **Interact with Assistant**
   Speak into your microphone to issue commands like:

  - “What’s the weather in [City]?” 🌤️
  - “Tell me the latest news.” 📰
  - “Set a reminder to [Task] at [Time].” ⏰
  
## 📂 Project Structure
  
    📁 Voice-Assistant  
    ├── assistant.py        # Core assistant script  
    ├── requirements.txt    # Python dependencies  
    ├── README.md           # Project documentation  
    ├── .env.example        # Template for storing API keys  



## 🎉 Sample Commands
Try these commands for a seamless experience:
- 🌤️ **Weather**: "What’s the weather in [City]?"
- 📰 **News**: "Tell me the latest news."
- 📅 **Reminders**: "Set a reminder to [Task] at [Time]."

The assistant will respond with accurate, real-time information.

## 🖥️ How It Works
- **Voice Input**: Listens to user commands via the microphone.
- **Command Processing**: Recognizes speech using speechrecognition and interprets tasks.
- **Task Execution**: Performs actions such as fetching weather data or setting reminders.
- **Spoken Response**: Responds audibly using the pyttsx3 library.

## 🌍 Future Enhancements
- 🧠 **AI-Powered Conversations**: Integrate advanced NLP for more human-like interactions.
- 📱 **Mobile Accessibility**: Expand functionality to mobile platforms.
- 🌎 **Multilingual Support**: Communicate in multiple languages for wider usability.

## 🤝 Acknowledgment
This project was completed as part of the CODEXINTERN Python Development Internship (December 2024). Grateful for the opportunity to learn and apply practical skills in Python development and API integration.

## 📜 License
This project is licensed under the MIT License. See the LICENSE file for details.

## 📧 Contact

- Email: khushidua110036@gmail.com
- GitHub: https://github.com/Khushi-Dua

Let’s make productivity smarter, one command at a time. 🚀
