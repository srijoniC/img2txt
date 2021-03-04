# img2txt
Img2Txt is a python wrapper to grab text from images and save as text files using Google Tesseract Engine. Tesseract is an optical character recognition engine for various operating systems. It is free software, released under the Apache License, Version 2.0, and development has been sponsored by Google since 2006. In 2006 Tesseract was considered one of the most accurate open-source OCR engines then available.
# Usage
python main.py -i <input_path> -o <output_path>
usage: main.py [-h] -i INPUT [-o OUTPUT] [-d]

required arguments:
  -i INPUT, --input INPUT       Single image file path or images directory path

optional arguments:
  -o OUTPUT, --output OUTPUT    (Optional) Output directory for converted text
  -d, --debug                   Enable verbose DEBUG logging
python main.py -i sample/
or

python main.py -i sample/ -o output/
Running Tests
python -m unittest
# Tesseract Installation
# Linux
[sudo] apt-get install tesseract-ocr
# Windows
Install tesseract-ocr from UB Mannheim here: https://github.com/UB-Mannheim/tesseract/wiki
Add the installed Tesseract-OCR directory path to PATH system variable
