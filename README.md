OCR to Text Converter  

A simple OCR PDF based text extractor using Python in Jupyter Notebook.  
This project extracts text from scanned PDFs using Tesseract OCR and saves the output as a '.txt' file.  

- Extracts text from scanned PDFs.
- Uses Tesseract OCR for text recognition.  
- Supports Colab and Google Drive integration.  

Installation  
1. Before running the notebook, install the required dependencies:  

!pip install pdf2image pytesseract opencv-python

How to Use
1. Upload your scanned PDF to Google Drive.
2. Modify the pdf_path in the code to match your uploaded file's path.
3. Run all cells in the Jupyter Notebook.
4. The extracted text will be saved as output.txt.

Code
You can find the full Jupyter Notebook (.ipynb) file in this repository. The main steps include:

1. Mounting Google Drive to access the PDF file
2. Converting PDF pages to images using pdf2image
3. Performing OCR on the images using pytesseract
4. Saving the extracted text to a .txt file