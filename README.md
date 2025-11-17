# Text-to-Speech Bot

## Description  
This project is a **Text-to-Speech Bot** built using the IBM Watson Text to Speech API.  
It allows users to convert any given text into an audio `.wav` file. Example use case: voice notifications, accessibility enhancements, automated announcements.

## Key Features  
- Convert input text to high-quality speech audio (.wav format)  
- Supports multiple voices/languages depending on IBM API settings  
- Easy command-line usage with one call:  
  ```bash
  curl -X POST -u "apikey:YOUR_API_KEY" \
    --header "Content-Type: application/json" \
    --header "Accept: audio/wav" \
    --data "{\"text\":\"Your text here\"}" \
    --output output.wav \
    "https://api.au-syd.text-to-speech.watson.cloud.ibm.com/instances/YOUR_INSTANCE_ID/v1/synthesize?voice=en-US_MichaelV3Voice"
