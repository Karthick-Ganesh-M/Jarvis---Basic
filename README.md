
# 🤖 Jarvis - Python Voice Assistant

Jarvis is a simple AI voice assistant built with Python. It can perform tasks like speaking the time, opening websites, launching applications, fetching information from Wikipedia, and more — all via voice commands!

## 🚀 Features

- Greets the user based on the time of day
- Listens to voice commands through the microphone
- Searches and reads summaries from **Wikipedia**
- Opens popular websites like YouTube, Google, Facebook, Instagram, and LeetCode
- Launches system applications like VS Code and Chrome
- Speaks responses using text-to-speech

## 🛠️ Requirements

Install the following Python libraries before running the script:

pip install pyttsx3
pip install SpeechRecognition
pip install wikipedia
pip install pyaudio

⚠️ If you face issues installing `pyaudio`, download the appropriate `.whl` file from:  
https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio  
Then install it using:  
pip install path_to_downloaded_file.whl

## 📁 Project Structure

Jarvis-Voice-Assistant/
├── main.py         # Main Python script  
└── README.md       # Project documentation

## 💻 How to Run

1. Clone this repository:  
git clone https://github.com/yourusername/Jarvis-Voice-Assistant.git

2. Navigate into the project folder:  
cd Jarvis-Voice-Assistant

3. Run the assistant:  
python main.py

## 🧠 Sample Voice Commands

- "Wikipedia Elon Musk"
- "Open YouTube"
- "Open Google"
- "Open Facebook"
- "Open Instagram"
- "What is the time?"
- "Open VS Code"
- "Open Chrome"
- "Open LeetCode"

## 📌 Notes

- Ensure your **microphone** is working and accessible.
- Requires **internet connection** for Wikipedia search and website launching.
- Best compatible with **Windows OS**.
- Remove or update the line `import chatgpt` unless you're planning to integrate ChatGPT.

## 📷 Screenshot

*(Add your screenshot here after uploading it to GitHub or using an image link)*

## 📄 License

This project is open-source under the MIT License.

## ✨ Credits

Created by **[Your Name]**  
Inspired by AI automation and J.A.R.V.I.S. from Iron Man.
