**AI MEDVoice**
---

 **About the Project**
 ---
AI MEDVoice is an intelligent **voice and vision-powered medical chatbot** designed to assist users in performing preliminary health symptom checks. This AI-driven virtual doctor understands voice input, analyzes medical images, and responds with smart, natural, and conversational advice — all through a simple, interactive web interface. AI MEDVoice combines state-of-the-art multimodal AI models with intuitive voice-based interaction to offer a realistic and user-friendly medical assistant. Whether you’re feeling unwell or just need quick guidance, AI MEDVoice aims to be your first step in seeking care — not a replacement for a real doctor, but a smart way to check your symptoms and get relevant insights.

**Built with:**
---
- Large Language Models for doctor-like responses
- Vision models to understand uploaded images
- Speech-to-text and text-to-speech for full voice interaction

 **Features**
---
- **Voice Input:** Speak your symptoms — AI converts your speech to text using **Whisper model**.
- **Image Input:** Upload medical images (rashes, injuries, etc.) for intelligent interpretation.
- **AI Diagnosis:** Uses **Llama-3.2-11B Vision models** doctor-style replies.
- **Audio Output:** AI reads responses aloud using text-to-speech.
- **User-Friendly UI:** Chat-like interface using **Gradio**.


 **Technology Stack**
---
- **Frontend:** Gradio (Python)
- **Audio Handling:** FFmpeg, PortAudio, PyAudio
- **AI Models:** 
  - Whisper (Speech Recognition)
  - Llama-3.2-11B (Vision-Language Model)

- **Backend:** Groq Cloud API

---

## Installation & How to Run

Follow these steps to install and run **AI MEDVoice** on your local machine:

#### Prerequisites

Make sure the following are installed:

- Python 3.8 or higher  
- `ffmpeg`  
- `portaudio` (for microphone support via PyAudio)  
- Git (to clone the repository)  
- A working **microphone and speaker**  

#### Step 1: Clone the Repository

```bash
git clone https://github.com/Priyanshu-Gupta777/AI-Doctor-Chatbot.git
cd AI-Doctor-Chatbot
```
#### Step 2: Create & Activate Virtual Environment

```bash
python -m venv venv
source venv/bin/activate       # Windows: venv\Scripts\activate
```
#### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```
#### Step 4: Install FFmpeg (if not already installed)
**Ubuntu/Debian:**

```bash
sudo apt install ffmpeg
```
**macOS (using Homebrew):**

```bash
brew install ffmpeg
```
**Windows:**

- Download from: https://ffmpeg.org/download.html

- Extract the ZIP

- Add the bin/ folder path to your System Environment Variables → PATH


#### Step 5: Add Your API Key
Create a .env file in the root directory:

```bash
GROQ_API_KEY = your_groq_cloud_api_key
```
#### Step 6: Run the App

```bash
python app.py
```
---

### Contact Information

If you have any questions or suggestions, feel free to reach out:

- **Email:** priyanshugp777@gmail.com
- **GitHub:** [Priyanshu-Gupta777](https://github.com/Priyanshu-Gupta777)

Feel free to open an **Issue** if you encounter any bugs or need help with the project!

