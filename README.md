# speech-to-text-tts-pipeline
An interactive end-to-end audio processing application utilizing OpenAI Whisper and SpeechT5 with a Gradio interface.
transformers>=5.0.0
dataset-2.0.0
soundfile>=0.13.1
torch>=2.11.0
gradio>=5.50.0
# Neural Speech Processing Pipeline: STT & TTS Deployment

An interactive, end-to-end audio deep learning application that features both Automatic Speech Recognition (ASR) and Neural Voice Synthesis. This project integrates state-of-the-art transformer models and deploys them via an intuitive web interface.

## 🚀 Features
* **Speech-to-Text (STT):** High-accuracy audio transcription utilizing the `OpenAI Whisper-small` pre-trained model.
* **Text-to-Speech (TTS):** Neural voice generation using `Microsoft SpeechT5` paired with a `HiFi-GAN` vocoder for realistic audio synthesis.
* **Interactive UI:** A user-friendly, tabbed web interface built with `Gradio` allowing seamless real-time audio recording, transcription, and speech generation.

## 🛠️ Tech Stack
* **Core Frameworks:** Python, PyTorch
* **Model Hub:** Hugging Face (Transformers)
* **Audio Processing:** SoundFile
* **Deployment/UI:** Gradio

