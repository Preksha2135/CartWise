# CartWise

## **Description**
This project is an AI-powered Optical Character Recognition (OCR) system that compares product details, such as price and quantity, from images of product packages. Users can upload images of the backs of two product packets, and the system extracts text from the images to output a comparison table of price and quantity. This tool leverages Tesseract OCR and OpenCV to pre-process and extract information from product images, offering a convenient solution for quick product comparison. This innovatie solution helps make informed purchasing decisions, saving time and money while ensuring they don't miss out on desired items.

## **Installation Instructions**
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Preksha2135/CartWise.git
   cd CartWise
   ```

2. **Install Dependencies:**
   Install the required libraries listed in `requirements.txt`:
   ```bash
   pip install -r requirements.txt
   ```

3. **Install Tesseract OCR:**
   Download and install Tesseract OCR. Add its path to your system’s environment variables.
   - **Windows**: [Download Tesseract](https://github.com/UB-Mannheim/tesseract/wiki).
   - **Linux/MacOS**: Install Tesseract via your package manager (e.g., `sudo apt install tesseract-ocr` for Ubuntu).

5. **Test the Installation:**
   Run the sample Jupyter notebook file to verify the setup:
   ```bash
   jupyter notebook CartWise.ipynb
   ```

## **Usage**
1. **Image Upload**: Upload images of the backs of two product packets.
2. **Comparison**: The system will preprocess images and use OCR to extract text data (price and quantity).
3. **Output**: A table displays the extracted information, comparing the products' prices and quantities.

## **Technology Stack**
- **Programming Language**: Python
- **Libraries**: 
  - **Tesseract OCR**: Optical Character Recognition
  - **OpenCV**: Image processing
  - **Pytesseract**: Python wrapper for Tesseract OCR
  - **Pillow**: Image handling and manipulation
  - **Jupyter Notebook**: Interactive development and testing environment

## **Authors/Credits**
- **Project Lead**: Preksha Jain (https://github.com/Preksha2135)
