# Resume Parser

A Python-based tool to **extract key information from resumes** in PDF format, including:

- Candidate's **Name**
- **Contact Number**
- **Email**
- **Skills**
- **Education**

The parser uses **PDFMiner** to extract text and **spaCy** + regex for intelligent data extraction.

---

## Features

- Extracts **Name** using spaCy's NER and proper noun analysis.
- Detects **Contact Number** with regex patterns.
- Extracts **Email Address** using regex.
- Finds **Skills** from a predefined skills list.
- Identifies **Education** information (Bachelor's, Master's, Ph.D., etc.).
- Works on multiple resumes in PDF format.

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/resume-parser.git
cd resume-parser
