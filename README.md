# Whisper AI Transcriber & Summarizer

## Overview
This project utilizes OpenAI's Whisper model for speech-to-text transcription and Facebook's BART model for text summarization. It allows users to upload an audio file, transcribe its content, and generate a concise summary.

## Features
- Automatic speech recognition (ASR) using Whisper
- Summarization of transcribed text using BART
- Interactive UI powered by Gradio
- Progressive Web App (PWA) support

## Installation
```bash
pip install openai transformers gradio torch
```

## Usage
Run the script to launch the Gradio interface:
```python
python app.py
```
Upload an audio file, and the system will generate a transcription along with a summary.

## Live Demo
Check out the live demo on Hugging Face Spaces:  
[Whisper AI Transcriber](https://huggingface.co/spaces/rayyanmoqeem/whisper-ai-transcriber)

## Blog Post
Read more about the project on Medium:  
[Whisper AI: Transcribing and Summarizing Speech with AI](https://medium.com/@razeenshahid47/whisper-ai-transcribing-and-summarizing-speech-with-ai-392cf42543d5)

## License
This project is open-source and available under the MIT License.
