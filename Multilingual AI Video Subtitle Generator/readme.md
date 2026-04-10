# 🎬 Multilingual AI Video Subtitle Generator

This project is an AI-powered system that automatically generates subtitles for videos and embeds them directly into the video output. It supports multiple languages and translates speech into English.

## 🚀 Overview

As part of a larger project, I implemented a speech-to-text pipeline and extended it to work with video inputs. The goal was to solve the problem of videos lacking subtitles, especially in regional or mixed languages, making them less accessible to a wider audience.

This system processes a video end-to-end:
- Extracts audio
- Converts speech to text
- Translates into English
- Generates subtitles
- Embeds subtitles back into the video

## 🔧 Features

- Multilingual speech recognition  
- Automatic translation to English  
- Subtitle generation (.srt format)  
- Subtitle embedding into video  
- Simple web interface using Gradio  

## 🛠️ Tech Stack

- Python  
- OpenAI Whisper  
- FFmpeg  
- Gradio  
- Hugging Face Spaces  

## ⚙️ How It Works

1. Upload a video file  
2. Audio is extracted using FFmpeg  
3. Whisper model processes the audio  
4. Speech is transcribed and translated  
5. Subtitles (.srt) are generated  
6. FFmpeg embeds subtitles into the video  
7. Final video is returned  

## 🌐 Live Demo

👉 [https://huggingface.co/spaces/Charanjot/ai-video-subtitle-generator]

## 📌 Performance Note

The application is currently deployed on CPU (Hugging Face free tier), so processing may take some time.  
With GPU access and larger models, the system can achieve faster and more accurate results.

## 📚 Learnings

- Implemented speech-to-text using Whisper  
- Worked with audio and video processing pipelines  
- Understood limitations of multilingual speech models  
- Gained experience in deploying AI applications  

## 🚧 Limitations

- Slower performance on CPU  
- Reduced accuracy for complex or low-resource languages  
- Processing time increases with video length  

## 🔮 Future Improvements

- GPU-based deployment for faster processing  
- Real-time subtitle generation  
- Improved translation using advanced language models  
- Speaker identification  

## 🤝 Contributing

Feel free to fork the repository and suggest improvements.

## 📄 License

This project is for educational and demonstration purposes.
