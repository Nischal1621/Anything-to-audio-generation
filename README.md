# Assistive System: Video-to-Audio & Image-to-Audio Generation

This project is designed to support visually impaired users by converting visual content into meaningful audio descriptions.

It includes:
- 🎥 **Video-to-Audio**: Extract frames from video → Recognize scenes/objects → Convert to speech
- 🖼 **Image-to-Audio**: Detect the content in images → Generate spoken feedback

This helps blind or low-vision users better understand surroundings by listening to audio information.

---

## ✨ Features

| Feature | Description |
|--------|-------------|
| Video Frame Extraction | Video is broken into key frames for interpretation |
| Object & Scene Recognition | AI model identifies objects, text, and context |
| Real-Time Audio Output | Text-to-speech conversion speaks detected content |
| Camera & Media Support | Supports webcam images or uploaded files |

---

## 🔧 Technologies Used
- **PyTorch** — Deep learning framework
- **Transformers (HuggingFace)** — Vision models like ViT, BLIP, or DETR
- **OpenCV** — Video capture & frame extraction
- **Speech engines** — `pyttsx3` (offline) / `gTTS` (online)
- **SpeechRecognition & pydub** — Optional audio utilities

---

## 📁 Project Workflow

### 1️⃣ Image-to-Audio
