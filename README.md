# Table Data Extraction OCR

![Image Preview](https://nanonets.com/blog/content/images/2019/12/Tesseract.gif) 

This project facilitates the extraction of table data from PNG or JPG images using OpenCV for table detection, cell recognition, and Pytesseract for Optical Character Recognition (OCR). The algorithm relies on detecting clear line structures within tables for accurate cell identification.

## Features

- **Table Detection:** Utilizes OpenCV to identify and isolate tables within images.
- **Cell Recognition:** Precisely allocates cells to their respective rows and columns.
- **OCR Extraction:** Employs Pytesseract for text extraction from allocated cells.

## Requirements

Ensure you have the following installed before running the code:
- Python 3.x
- OpenCV
- Pytesseract
- Other dependencies listed in `requirements.txt`

## Usage

1. **Installation:**

   ```bash
   # Clone the repository
   git clone https://github.com/your_username/your_repository.git
   cd your_repository

   # Install dependencies
   pip install -r requirements.txt

1. **Running the Algorithm:**

- Provide PNG or JPG images containing tables as input files.
- Run the main script for table data extraction:
    ```bash
   python table_extraction.py path/to/input_image.png

- Or experiment with the Jupyter Notebooks
    ```bash
    jupyter notebook
1. **Output:**

- The algorithm generates an Excel (.xlsx) file as output, containing the extracted table data organized within sheets.

## References

- OpenCV Documentation: OpenCV: OpenCV modules
- Pytesseract Documentation: Pytesseract
