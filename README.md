# redactIQ
The project introduces a sensitive information redaction system called RedactIQ. This system processes documents in multiple formats, extracts text content, identifies sensitive entities using machine learning models, applies pattern-based detection for structured data, and generates redacted documents with optional digital signatures.
# RedactIQ

RedactIQ is an AI-based document redaction system that automatically detects and removes sensitive information from documents. The system helps prevent accidental or malicious data leakage by sanitizing documents before they are shared.

## Features

* Automatic detection of sensitive data using NLP
* Redaction of names, locations, organizations
* Detection of emails, phone numbers, and Aadhaar numbers using regex
* Supports multiple document formats: **TXT, PDF, DOCX**
* Generates redacted documents for secure sharing
* Basic document analysis and visualization
* Digital signature support for document verification

## Technologies Used

* Python
* Flask
* spaCy (NLP)
* PyPDF2
* python-docx
* FPDF
* TextBlob
* Matplotlib
* Pandas

## Installation

Clone the repository:

git clone https://github.com/your-username/RedactIQ.git

Navigate to the project folder:

cd RedactIQ

Install dependencies:

pip install -r requirements.txt

Download spaCy model:

python -m spacy download en_core_web_sm

Run the application:

python app.py

Open the application in your browser:

http://127.0.0.1:5000

## Usage

1. Upload a document (TXT, PDF, or DOCX)
2. The system analyzes the document
3. Sensitive information is detected
4. A redacted version of the document is generated
5. Download the sanitized document

## Author

Lokesh S
