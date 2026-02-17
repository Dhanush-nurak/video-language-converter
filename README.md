# Video Language Converter (AI/NLP) 🎥

![Python](https://img.shields.io/badge/Python-FFD43B?logo=python&logoColor=blue)
![NLP](https://img.shields.io/badge/AI-NLP-green)
![Whisper](https://img.shields.io/badge/Model-Whisper-violet)

## 📌 Overview
This project is an automated pipeline that takes a video input, extracts speech using **OpenAI's Whisper model**, translates it into a target language, and generates synchronized subtitles. It streamlines the process of creating multi-language content for video platforms.

## 🚀 Features
- **Audio Extraction**: Automatically separates audio tracks from video files.
- **Speech-to-Text**: Utilizes Whisper AI for high-accuracy transcription.
- **Translation**: Translates transcripts into multiple target languages using NLP transformers.
- **Subtitle Generation**: Outputs `.srt` files synchronized with the video.

## 🛠️ Tech Stack
- **Language**: Python
- **AI Models**: OpenAI Whisper (ASR), HuggingFace Transformers
- **Video Processing**: MoviePy
- **Tools**: FFmpeg

## ⚙️ How to Run
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
