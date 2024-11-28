# English to Mongolian Subtitle Translator & Text-to-Speech Converter

This project leverages the **Chimege Text-to-Speech API** and provides two main functionalities:
1. **Translate English to Mongolian Subtitles**: Supports `.srt` files with timecodes and generates translated Mongolian `.srt` files.
2. **Text-to-Speech (TTS)**: Converts text input (or subtitles) to realistic Mongolian audio.

---

## Features
- **English to Mongolian Translation**:
  - Translate plain English text.
  - Translate `.srt` subtitle files while retaining timecodes.
- **Text-to-Speech (TTS)**:
  - Generate Mongolian speech from text or translated subtitles.
- **Output Formats**:
  - Translated `.srt` files.
  - Synthesized audio files (`.mp3` or `.wav`).

---

## Technologies Used
- **Programming Language**: Python
- **APIs**:
  - **Chimege TTS API** for speech synthesis.
  - Currently using Selenium Webdriver to translate texts using Google Translate

---

## Prerequisites
1. **Chimege API Key**:  
   Obtain your API key from [Chimege API](https://console.chimege.com/login).

**Example**

Input (input_file.srt):
1
00:00:01,000 --> 00:00:03,000
Hello, how are you?

2
00:00:04,000 --> 00:00:06,000
Welcome to the tutorial.

Output (output_file_mn.srt):
1
00:00:01,000 --> 00:00:03,000
Сайн байна уу, та хэр байна?

2
00:00:04,000 --> 00:00:06,000
Энэ хичээлд тавтай морил.

**Future Improvements**

	•	Add support for batch processing.
	•	Integrate other languages for multi-lingual support.
	•	Add a front-end for user-friendly input/output handling.

 
**Contributing**

Feel free to open issues or submit pull requests to contribute to this project.
