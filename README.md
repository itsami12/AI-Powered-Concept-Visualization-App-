# AI-Powered-Concept-Visualization-App-
An intelligent math-solving web application that explains math problems step-by-step using the DeepSeek-Math-7B-Instruct model. It goes beyond traditional solvers by generating:

- ✅ Textual explanations
- 🗣️ Audio narrations (Text-to-Speech)
- 🖼️ Visual image displays
- 🎞️ Educational video generation with audio and overlayed text

## 🔍 How It Works

1. **Input:** User provides a math question.
2. **AI Explanation:** The DeepSeek model generates a detailed step-by-step explanation.
3. **Text-to-Speech:** Converts the explanation into audio using gTTS.
4. **Image Generation:** Uses matplotlib to create an image with the explanation.
5. **Video Creation:** Combines image + audio into a short video using OpenCV or FFmpeg.
6. **Response:** The generated explanation, audio, image, and video are returned via a Flask API.

## 🚀 Features

- 📚 Natural language explanations of complex math problems
- 🧏‍♂️ Text-to-Speech conversion using Google TTS
- 🖼️ Auto-generated visuals with clear math formatting
- 🎬 Automatic video generation for learning or sharing
- 🌐 Public server access via ngrok

## 🧠 Model Used

- [DeepSeek-Math-7B-Instruct](https://huggingface.co/deepseek-ai/deepseek-math-7b-instruct)

## 🛠️ Installation

```bash
pip install --upgrade pip

# Hugging Face Transformers and login support
pip install transformers
pip install huggingface_hub

# Google Text-to-Speech
pip install gTTS

# Jupyter tools (optional, for Audio playback in notebooks)
pip install IPython

# Flask web framework
pip install Flask

# Others (optional or indirect dependencies)
pip install matplotlib
pip install moviepy
pip install torch
pip install opencv-python
pip install flask-ngrok  # if you're using ngrok with Flask
