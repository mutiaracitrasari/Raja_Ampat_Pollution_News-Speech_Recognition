# Raja Ampat Pollution News Speech Recognition

This project is a case study on transcribing a news audio report related to pollution in Raja Ampat using two state-of-the-art speech recognition approaches: **Google Web Speech API** and **OpenAI Whisper**.

## Project Objectives

* Transcribe a `.wav` audio file containing a news report
* Compare transcription outputs from Google Web Speech API and OpenAI Whisper
* Evaluate transcription accuracy using **Word Error Rate (WER)** and **Character Error Rate (CER)**

## Technologies & Libraries

* Python
* [SpeechRecognition](https://pypi.org/project/SpeechRecognition/)
* [OpenAI Whisper](https://github.com/openai/whisper)
* [gTTS (Google Text-to-Speech)](https://pypi.org/project/gTTS/)
* [Librosa](https://librosa.org/)
* [JiWER](https://pypi.org/project/jiwer/)
* Matplotlib

## Notebook Overview

1. **Library Installation & Imports**
2. **Audio Visualization** — Displays waveform and spectrogram of the input audio
3. **Transcription Using Google Web Speech API**
4. **Transcription Using OpenAI Whisper**
5. **Comparison of Transcriptions**
6. **Evaluation with WER & CER Metrics**
7. **Text-to-Speech Synthesis** of the transcribed results

## How to Use

1. Ensure the `news.wav` file is in your working directory.
2. Open and run each cell in the notebook:
   `Raja_Ampat_Pollution_News_Speech_Recognition.ipynb`
3. The transcriptions and evaluation metrics will be displayed as outputs.

## Evaluation

The transcription accuracy is measured using the following metrics:

* **WER (Word Error Rate)** – evaluates word-level differences between reference and hypothesis
* **CER (Character Error Rate)** – evaluates character-level transcription accuracy

