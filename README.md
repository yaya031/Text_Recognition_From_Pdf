
# PDF Image Text Extractor

This project demonstrates how to extract and recognize text from images embedded within a PDF document using Python. It utilizes the PyPDF2 library to manipulate PDF files, PIL (Python Imaging Library) for image processing, and pytesseract, a Python wrapper for Google's Tesseract-OCR Engine, to convert images into text.

## Installation

To set up this project, you will need Python installed on your system. Follow the steps below to install the required libraries.

1. Clone this repository or download the source code.
2. Open your terminal or command prompt.
3. Navigate to the project directory.
4. Install the required libraries using pip:

```bash
pip install PyPDF2 Pillow pytesseract
```

Note: You might also need to install Tesseract-OCR on your system. Please refer to the [Tesseract-OCR GitHub page](https://github.com/tesseract-ocr/tesseract) for installation instructions specific to your operating system.

## Usage

To use this script, follow these steps:

1. Place your PDF file in the same directory as the script or specify the path to your PDF file in the `pdf_file` variable.
2. Run the script with:

```bash
python pdf_image_text_extractor.py
```

3. The script will print the extracted text from the images embedded in the PDF file to the console.

## Example

Given a PDF file `TrialPDF.pdf` with embedded images, running the script will output the text recognized in those images.




