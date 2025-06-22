# PDF-Merger
- ## Project Overview
  - PDF Merger is a lightweight Python-based tool designed to combine multiple PDF files into a single, organized PDF document. It's especially useful for merging scanned documents, research papers, receipts, certificates, or multi-part PDFs into a unified file for storage, sharing, or printing.

## Features
- Merge multiple PDF files in the order you choose
- Automatically name and save the output PDF
- Simple and minimal interface — no bloat
- Works for PDFs of any length or size


## Libraries Used:
- `PyPDF2` – for PDF merging and handling
- `os` – for file management


## Requirements
- Before running the project, make sure to install dependencies:
````
pip install PyPDF2
````

## How It Works
- ### Load the PDFs — list the paths of the PDF files you want to merge
- ### Merge them — combine all into one file using PyPDF2.PdfMerger()
- ### Save the output — write the merged content to a new .pdf file

## Steps to Run
- ### Clone the Repository
````
git clone https://github.com/CodeCrafter-101/pdf-merger.git
cd PDF-Merger
````
- ### Install Required Libraries
````
pip install PyPDF2
````
- ### Run the Script
````
python pdf_merger.py
````
- ### Merged PDF
    - The merged PDF will be saved with the name specified in the `output_pdf` variable.

## Notes
- PDFs must not be password-protected (PyPDF2 doesn't support encrypted PDFs by default)
- File order in the list determines the order in the merged document




