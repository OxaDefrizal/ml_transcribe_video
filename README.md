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
```
## Usage
1. Clone the repository: https://github.com/OxaDefrizal/ml_transcribe_video.git
2. Run the script:
3. Enter the YouTube video URL when prompted.
4. The script downloads the audio, transcribes it into text, and saves it in a text file (e.g., Hasil Transcribe_en.txt). The language is automatically detected.

## Dependencies
* PyTube: Fetch YouTube content.
* Whisper ASR: OpenAI's ASR model.
* Langdetect: Detects the language of the transcribed text.

## How it Works
1. YouTube Video Input: User provides the YouTube video URL.
2. Audio Download: PyTube downloads the audio stream.
3. Transcription: Whisper ASR transcribes the audio.
4. Language Detection: Langdetect determines the language.
5. Text Output: Transcribed text saved in a file with language info.


## License
Contributions are welcome. Report issues or suggest improvements via GitHub.
