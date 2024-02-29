# Information-Extraction-and-Web-Navigation
Automating Information Extraction and Web Navigation with PyTesseract and Google Search API

This project focuses on simplifying the tasks of extracting information from images and efficiently navigating the web. We're using two tools: PyTesseract for converting images to text and a web crawler with the Google Search API. The main objective is to automate the process of getting a list of 127 company names from an image and then finding career page links online.

Starting with PyTesseract, it's a Python tool that helps us convert the visual data of 127 company names from an image into readable text. This eliminates the need for manual data entry and ensures accuracy.

Moving on to the web crawler, we use the Google Search API to search for career page links related to the identified companies. This integration makes our web searches more targeted and efficient, saving time and effort.

To initiate the project, I set up a new conda environment dedicated to this task. This ensures a clean and isolated space for our project. Then we install the required libraries for this project, for example Pillow to read the images.

Unlike some other libraries that can be installed with a simple 'pip install' statement, using PyTesseract requires an additional step due to its dependence on the Tesseract OCR engine. (OCR - Optical Character Recognition)

Specifically:

For Windows users, it's necessary to download the Tesseract executable file. The path to this executable needs to be specified in the PyTesseract configuration. This ensures that PyTesseract can utilize the Tesseract OCR engine correctly. Here is the link to download tesseract for windows


For macOS users, installation guidelines for Tesseract on a Mac are available. Following these guidelines ensures that PyTesseract functions seamlessly. Here is the link to install tesseract for mac

If you want more information on tesseract, use the following resources:

https://github.com/tesseract-ocr/tesseract
https://pypi.org/project/pytesseract/

Please refer the jupyter notebook for more details on the code. Happy coding!
