# File Converter Application

A lightweight and user-friendly web application to convert files between different formats. The application is built using Python and Flask, providing support for Word, Excel, and CSV file conversions to PDF and web view formats.

## Features

- **Supported Input Formats:** Word, Excel, CSV.
- **Supported Output Formats:** PDF, Web View.
- Converts tabular data to PDF with dynamic table layouts.
- Unicode support for text in PDF generation.
- Simple and interactive web interface.

## Installation

1. **Clone the Repository**:
```bash
   git clone https://github.com/your-username/file-converter.git
   cd file-converter
```
2. Install Dependencies: Make sure you have Python installed. Then run:
```bash
   pip install -r requirements.txt
```
3. **Run the Application**:
```bash
   python app.py
```

4. **Access the Application**: Open your web browser and navigate to:
```bash
   http://localhost:5555
```


## Usage
    Upload a file via the web interface by dragging and dropping it into the upload area or clicking to browse your system.
    Select the input file format (Word, Excel, CSV).
    Choose the output format (PDF, Web View).
    Click "Convert" to process the file.
    Download the converted file or view the output.

## File Structure
```bash
file-converter/
│
├── app.py             # Main Flask application
├── templates/
│   └── index.html     # HTML template for the web interface
├── requirements.txt   # Python dependencies
└── static/
    └── DejaVuSans.ttf # Unicode font used for PDF generation
```
## Dependencies
    Python Libraries:
        Flask
        pandas
        fpdf
        python-docx

    Additional Files:
        DejaVuSans.ttf: A Unicode font required for PDF text rendering.

**Install the dependencies using:**
```bash
pip install flask pandas fpdf python-docx
```
