# project3
BizCardX: Extracting Business card data with OCR

NAME: D.KARTHIKA
BATCH CODE: DW77DW78

# BizCardX---Business-Card-Data-Extraction with ocr

BizCardX is a Python application that allows users to upload an image of a business card and extract relevant information from it using Optical Character Recognition (OCR). This information includes the company name, card holder name, designation, mobile number, email address, website URL, area, city, state, and pin code. The extracted information can be displayed in the application's graphical user interface (GUI), and users can save it to a database. Users can also view , update, and delete the stored data through the Streamlit UI.

## Technologies Used

- Python
- Streamlit
- easyOCR
- postgresql


## Approach

1. **Install Required Packages**: Install Python, Streamlit, easyOCR, and a database management system such as psycopg2.

2. **Design User Interface**: Create an Streamlit interface for uploading business card images and information extraction.

3. **Implement Image Processing and OCR**: Use easyOCR to extract information from uploaded images with image processing techniques.

4. **Display Extracted Information**: Present the extracted information in an organized manner in the Streamlit GUI.

5. **Database Integration**: Store extracted data and images in a database using SQL queries.

## What is EasyOCR?

EasyOCR, as the name suggests, is a Python package that allows computer vision developers to effortlessly perform Optical Character Recognition.It is a Python library for Optical Character Recognition (OCR) that allows you to easily extract text from images and scanned documents. In my project I am using easyOCR to extract text from business cards.

**When it comes to OCR, EasyOCR is by far the most straightforward way to apply Optical Character Recognition***:

1.The EasyOCR package can be installed with a single pip command

2.Once EasyOCR is installed, only one import statement is required to import the package into your project.

3.From there, all you need is two lines of code to perform OCR - one to initialize the Reader class and then another to OCR the image via the readtext function.
