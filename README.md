# 🎥 Video Summarizer

This project automatically generates a **summary video** from a long video by:  
1. **Transcribing** the audio using OpenAI's [Whisper](https://github.com/openai/whisper).  
2. **Extracting key snippets** from the transcript using [KeyBERT](https://github.com/MaartenGr/KeyBERT).  
3. **Cutting and merging clips** based on the key snippets using [FFmpeg](https://ffmpeg.org/).  

It’s designed for quickly condensing long lectures, podcasts, and talks into a shorter highlight reel.

---

## 🚀 Features
- 🎙️ **Speech-to-text transcription** with timestamps using Whisper  
- 🔑 **Keyword-based summarization** of transcripts with KeyBERT  
- ✂️ **Automatic video clipping** around important transcript segments  
- 📹 **Final summary video generation** using FFmpeg  

---

## 🛠️ Tech Stack
- **[Python 3.x](https://www.python.org/)**  
- **[OpenAI Whisper](https://github.com/openai/whisper)** – for speech-to-text transcription  
- **[KeyBERT](https://github.com/MaartenGr/KeyBERT)** – for extracting important keywords/snippets  
- **[Pandas](https://pandas.pydata.org/)** – for handling transcription data  
- **[FFmpeg](https://ffmpeg.org/)** – for trimming and merging video clips  

---

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/anirudhreddy000/video_summarizer.git
   cd video_summarizer
