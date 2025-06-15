# Voice-Activated Virtual Assistant using NLP and Transformers

This project implements a lightweight, offline-capable Voice-Activated Virtual Assistant that performs basic intent detection, text simplification using pre-trained NLP models, and speech synthesis using open-source Python libraries.

---

## Project Overview

- **Intent Detection**: Rule-based keyword matching for common queries like time, date, jokes, and greetings.
- **Text Simplification**: Simplifies complex sentences using the T5-small Transformer model from Hugging Face.
- **Speech Synthesis**: Converts text responses to speech using Google Text-to-Speech (gTTS).
- **Execution Environment**: Google Colab or local Jupyter Notebook.
- **Offline Operation**: Fully offline after initial model download.

---

## Technologies Used

- Python 3.x
- Transformers (Hugging Face)
- T5-small pre-trained model
- gTTS (Google Text-to-Speech)
- IPython Display (for audio playback)
- datetime (for time & date functions)
- os (for file handling)

---

## ⚙ Installation & Setup
 Install required libraries:
```bash
pip install transformers gTTS torch IPython
Load the pre-trained T5-small model from Hugging Face
Clone or download this repository and run the provided notebook or Python file.
