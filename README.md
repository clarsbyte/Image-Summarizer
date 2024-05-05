# Image-Summarizer
Uses Tesseract and Google's Gemini Pro to summarize text displayed in an image. 

Here are the libraries you'll need to install:
1. `pip install Pillow`
1. `pip install -U google-generativeai` 

You can visit Gemini Pro's documentation [here](https://ai.google.dev/gemini-api/docs/get-started/python)

2. `pip install pytesseract` 

[Download](https://github.com/UB-Mannheim/tesseract/wiki) the .exe file.

## How to use
1. Set up your Gemini Pro API Key.
2. Edit path to `tesseract.exe` file.
3. Simply provide a path of an image to the input and a following summary will be outputted. 
