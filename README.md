# YouTube Transcription using Python

This repository provides a simple Python script to transcribe audio from YouTube videos into text. The script uses the PyTube library to download audio from a YouTube video, the Whisper ASR (Automatic Speech Recognition) model for transcription, and Langdetect for language detection.

## Table of Contents
1. [Installation](#installation)
2. [Usage](#usage)
3. [Dependencies](#dependencies)
4. [How it Works](#how-it-works)
5. [License](#license)

## Installation

Before running the script, make sure to install the required dependencies:

```bash
!pip install pytube
!pip install git+https://github.com/openai/whisper.git
!pip install langdetect

git clone https://github.com/your-username/your-repository.git
cd your-repository

python transcribe_youtube.py
