Optical Character Recognition (OCR) program to reconstruct and extract texts from images and photos.
Access or program: https://share.streamlit.io/guilhermedonizetti/ocr_python/main.py


Objective: The visa program receives an image as input, reconstitutes the characters contained therein and extracts these characters. Once the text was extracted, the program estimates how many percent of words, or more, there is no text from the image based on a small set of pre-registered words. Finally, the program seeks to find CPF and data.

Tools:
✔️ Pytesseract - Python library for OCR applications, documents (https://pypi.org/project/pytesseract/).
✔️ Streamlit - Python framework for website construction, documentation (https://docs.streamlit.io/en/stable/).

Operation: The program is going to access the images on your device, some points must be observed:
👉 The program interprets texts in Portuguese 🇧🇷 or languages ​​with a similar alphabet (ex.: 🇺🇸).
👉 The result depends on the quality of the image.
👉 It is more assertive for the image to be rotated with vertical text

When the characters are remade, the logo will be displayed below the image and on the left side of the page the option to Analyze text appears. If this option is selected for the program, you will search for:
