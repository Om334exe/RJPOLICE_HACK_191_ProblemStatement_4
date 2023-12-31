# FIR Analysis Project 🕵️‍♂️📋

This project utilizes OCR (Optical Character Recognition) and other technologies to analyze Sample First Information Reports (FIRs) and extract crucial information. The goal is to provide insights into crime types, details, and related legal sections.
## Project Overview 📑
**Note**: Project is Still Under Development , Some components already there and some are under development process
The project involves the following key components:

1. **OCR and Text Extraction**: Utilizes the EasyOCR library for OCR to extract text and bounding boxes from images of FIRs.

2. **Crime Information Extraction**: Parses the OCR results to identify the crime type and details. Draws bounding boxes around relevant information on the image.

3. **PDF Search**: Converts PDFs containing Indian crime laws into images and performs keyword searches using regular expressions. Identifies matches and extracts related legal section numbers.

4. **IndiaCode Integration**: Searches on the IndiaCode platform to find additional information related to the identified crime type.

## How to Use 🚀

1. **Image Processing**: Provide the path to the image of the FIR (`SampleFIR.png`) to initiate the analysis.

2. **Visualization**: The image will be displayed with bounding boxes around the identified crime type and details.

3. **PDF Search**: If crime information is complete, the project searches a PDF file (`criminal_laws.pdf`) for matches, highlighting type and details, and providing section numbers.

4. **IndiaCode Integration**: Additional information related to the crime type is fetched from the IndiaCode platform.

## Important Note 📝

- **Sample Data**: The project is currently using sample FIR data (`SampleFIR.png`) and a document of crime laws (`criminal_laws.pdf`) for analysis.

- **Section Identification**: In further development, the project aims to identify specific legal sections related to the identified crime types.

- **Web Scraping**: The project includes web scraping from the IndiaCode site to enhance the information retrieval process.

## Requirements 🛠️

Make sure you have the following Python libraries installed:

- `re`
- `easyocr`
- `requests`
- `bs4` (BeautifulSoup)
- `pdf2image`
- `matplotlib`
- `PIL` (Pillow)
## Web Interface
The main page (index.html) allows users to upload an image of an FIR for analysis.
The result page (result.html) displays crime details and relevant laws extracted from the analysis.
## Screenshot ( Demo Website Overview)
![Screenshot from 2023-12-19 11-04-23](https://github.com/Om334exe/RJPOLICE_HACK_191_ProblemStatement_4/assets/134759580/b22fa463-eb4e-4b93-9403-488a0d76248d)
Please note that the project is still in progress and incomplete. It will become even better after completion.

## Team Information
This web application is developed by Team Adhunikta, consisting of Om Dabral and Saksham Srivastava.

Feel free to explore the web application and contribute to its further development!
