
# Multilingual AI Assistant

## Overview
This is a **Multilingual AI Assistant** built using Streamlit. It allows users to ask questions via voice input, processes the input using an AI model, and responds with both text and speech output.

## Features
- Voice-based input
- AI-powered response generation
- Text-to-speech conversion
- Audio playback of responses
- Option to download the response as an audio file

## Installation
To run this application locally, follow these steps:

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd multilingual-ai-assistant
   ```

2. **Create a virtual environment (optional but recommended)**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On macOS/Linux
   venv\Scripts\activate     # On Windows
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. **Run the Streamlit app**
   ```bash
   streamlit run app.py
   ```
2. Click the **"Ask me anything!"** button to start recording your question.
3. The AI processes your question and provides a response in text.
4. The response is also converted into speech and can be played or downloaded.

## File Structure
```
multilingual-ai-assistant/
│── src/
│   ├── helper.py          # Contains voice input, AI processing, and TTS functions
│── app.py                 # Main Streamlit application
│── requirements.txt        # Python dependencies
│── README.md               # Project documentation
```

## Dependencies
This project requires the following libraries:
- **Streamlit** (for the UI)
- **SpeechRecognition** (for voice input processing)
- **geminiAPI** (for AI-powered responses)
- **gTTS** (for text-to-speech conversion)

Ensure all dependencies are installed using the `requirements.txt` file.

## Contributing
Feel free to contribute to this project by improving the AI model, enhancing the UI, or optimizing the voice processing pipeline. Fork the repository and submit a pull request with your changes.

## License
This project is licensed under the MIT License.

## Contact
For any queries or suggestions, please reach out via GitHub or email.

---
Enjoy using the **Multilingual AI Assistant**! 🚀

