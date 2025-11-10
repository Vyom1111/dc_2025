# Invoice GenAI Project 🧾

## 🚀 Overview

Welcome to the **Invoice GenAI Project**! This cutting-edge application leverages the power of Streamlit, Optical Character Recognition (OCR), and advanced language models to streamline the extraction of key details from invoice PDFs. Our tool efficiently extracts customer information, product details, and total amounts, presenting a clean and user-friendly interface for effortless invoice processing.

## ✨ Features

- **📄 PDF Upload**: Seamlessly upload multiple PDF invoices for processing.
- **🔍 Information Extraction**: Automatically identifies and displays customer details, product lists, and total amounts.
- **🖼️ OCR Integration**: Harnesses Tesseract OCR to extract text from images embedded in PDFs.
- **🤖 Generative AI**: Utilizes Google Generative AI (Gemini) for precise text analysis and extraction.

## 🛠️ Prerequisites

Ensure you have the following installed before you start:

- **Python**: Version 3.7 or higher.
- **System Packages**: Tesseract OCR.

## 📦 Installation

Follow these steps to get the project up and running:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/MalaiarasuGRaj/Invoice-GenAI-Project.git
   cd invoice-genai-project

2. **Set Up the Virtual Environment**
    Create and activate a virtual environment to manage dependencies:

    python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`

3. **Install Python Dependencies**

    Install the required Python packages using requirements.txt:
    pip install -r requirements.txt

4. **Install System Packages**

    Tesseract OCR is required for image-based text extraction. Install it using:
    sudo apt-get install tesseract-ocr

5. **Download SpaCy Model**

    Download the SpaCy model needed for text processing:
    python -m spacy download en_core_web_sm

6. **Configure API Key**
    Open InvoiceExtracter.py and insert your Google Generative AI API key where indicated.

**🏃‍♂️ Usage**

**1. Run the Streamlit Application**

    Start the Streamlit app by executing:
    streamlit run InvoiceExtracter.py

**2. Access the Application**
    Open your web browser and go to the URL provided by Streamlit, usually http://localhost:8501.

**3. Upload Invoices**

   Use the file uploader in the sidebar to upload your PDF invoices.
   The application will process the files and display extracted details, including customer information, product lists, and total amounts.

**🧩 Code Overview**

   - InvoiceExtracter.py: Main script for running the Streamlit application. Handles PDF uploads, text and image extraction, and uses the generative AI model for extracting invoice details.
   - requirements.txt: Lists the Python dependencies required for the project. Install these using pip install -r requirements.txt.
   - sample_invoices/: Contains example PDF invoices used for testing the extraction functionality.
   - output/: Includes screenshots showcasing the application in use, Provides video recordings of the application's workflow for a visual demonstration.

**🛠️ Troubleshooting**

   - Extraction Issues: Ensure the PDFs are not encrypted or password-protected, Tesseract OCR is correctly installed, and the API key is valid and correctly configured.
   - Error Messages: Check Streamlit logs for detailed error messages to assist in debugging.

**🤝 Contributing**

   - Contributions to improve the project are welcome! To contribute:
   - Fork the repository.
   - Create a new branch for your changes (git checkout -b feature-branch).
   - Make your changes and commit them (git commit -am 'Add new feature').
   - Push your branch to GitHub (git push origin feature-branch).
   - Open a pull request to merge your changes.

**📧 Contact**
    For any questions or feedback, feel free to reach out:
    Email: govindarajmalaiarasu@gmail.com
    LinkedIn: Malaiarasu G Raj (www.linkedin.com/in/malaiarasu-g-raj-38b695252)
