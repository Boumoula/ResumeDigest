# CVDigest: NLP-Powered Resume Analysis Tool

CVDigest is a tool designed for HR professionals to automate the extraction of relevant information from resume (CV) files in PDF format. It uses a Named Entity Recognition (NER) model based on Transformer architectures to identify and extract structured data from unstructured documents.

## Features

- Extracts names, contact details, skills, diplomas, dates of birth, gender, language skills, and more
- Supports processing of one or multiple PDF CVs at once
- Outputs a structured CSV or XLSX file with one row per CV
- Includes a graphical user interface built with Streamlit
- Uses a custom-trained RoBERTa model integrated into a spaCy pipeline
- Text is extracted from PDFs using PyMuPDF

## Output Format

The output is a structured file (CSV or XLSX) with at least the following columns:

- Name
- First Name
- Date of Birth
- Gender
- Skills
- Diploma
- Other
- Language Skills
