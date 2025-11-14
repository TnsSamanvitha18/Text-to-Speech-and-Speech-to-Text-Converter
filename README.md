# 🎙️ Text-to-Speech and Speech-to-Text Converter V2

## 📌 Overview
This project bridges the gap between **human speech and digital text** by implementing a **bidirectional converter** that can transform **text into natural-sounding speech** and **speech into accurate text**.  
It also includes an **accuracy evaluation module** that calculates **Word Error Rate (WER)** to measure transcription quality.  
The entire system is wrapped in an intuitive **Gradio-based user interface** for easy real-time interaction.

---

## 🚀 Features
- 🔊 **Text-to-Speech (TTS)** using Google Text-to-Speech (`gTTS`)  
- 🗣️ **Speech-to-Text (STT)** using Facebook AI’s `Wav2Vec2` model  
- 📈 **Accuracy Checker** using `JiWER` (Word Error Rate)  
- 🌐 **Interactive Gradio Interface**  
- ⚙️ Runs directly in **Google Colab** or locally via Python  

---

## 🧠 Objective
- To develop a system that allows **bidirectional conversion** between text and speech.  
- To provide an **interactive interface** for real-time conversion and accuracy testing.  
- To evaluate model performance using **WER and accuracy percentage**.  

---

## 🧩 Tech Stack
| Component | Library/Tool |
|------------|--------------|
| Programming Language | Python |
| Speech Recognition | Wav2Vec2 (Hugging Face Transformers) |
| Speech Synthesis | gTTS |
| Audio Processing | Librosa, SoundFile |
| Evaluation Metric | JiWER |
| Frontend Interface | Gradio |

---

## ⚙️ How It Works
1. **Input Capture** — User enters text or records speech.  
2. **Text-to-Speech Conversion** — `gTTS` converts text into an audio file.  
3. **Speech-to-Text Conversion** — `Wav2Vec2` processes the audio and generates text output.  
4. **Accuracy Evaluation** — `JiWER` compares the original and transcribed text to compute **WER** and **accuracy %**.  
5. **Gradio Interface** — Provides an interactive GUI with three tabs: *Text → Speech*, *Speech → Text*, and *Accuracy Checker*.

---

## 📊 Results
- Accurate **speech recognition** and **text synthesis**  
- Easy-to-use **web interface**  
- Real-time conversion with measurable **accuracy metrics**

---

## 🔮 Future Scope
- Support for **multiple languages and accents**  
- Integration into **voice assistants** and **accessibility tools**  
- **Noise-robust model** for real-world audio  
- Deployment as a **mobile or web application**

---

## 📚 References
1. [Wav2Vec2 - Facebook AI](https://huggingface.co/facebook/wav2vec2-base-960h)  
2. [Google Text-to-Speech (gTTS)](https://pypi.org/project/gTTS/)  
3. [JiWER (Word Error Rate Metric)](https://pypi.org/project/jiwer/)  
4. [Gradio Documentation](https://www.gradio.app/)

---

## 👩‍💻 Authors
- **T.N.S. Samanvitha**  
- **P. Amulya**  
- **P. Phani Krishna**
