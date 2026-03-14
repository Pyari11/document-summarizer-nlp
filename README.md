# NLP-Based Multi-Format Document Summarizer
A Python-based Natural Language Processing (NLP) tool that summarizes
documents in multiple formats including **PDF, DOCX, and TXT**.

The system automatically detects important sentences and generates
**structured bullet-point summaries**, making large documents easier
to understand.

This project was developed and tested using **Jupyter Notebook**.

## Features
- Supports multiple document formats:
  - PDF
  - DOCX
  - TXT
- Automatic **heading detection**
- **Bullet-point summaries** for readability
- Handles **large documents with page limits**
- Extractive summarization using **NLP techniques**

## Technologies Used
- Python
- NLTK (Natural Language Toolkit)
- PyPDF2
- python-docx
- Jupyter Notebook

## How the System Works
Input Document
↓
Text Extraction (PDF / DOCX / TXT)
↓
Sentence Tokenization
↓
Word Frequency Analysis
↓
Sentence Scoring
↓
Bullet-Point Summary

## Installation
Install required libraries:
pip install PyPDF2 python-docx nltk

## Running the Program
Run the notebook or script and provide the document path:
Enter file path (.pdf, .docx, .txt):example.pdf
Output will display a **bullet-point summary** of the document.

## Example Output
Detected Headings
▶ INTRODUCTION
▶ MACHINE LEARNING
▶ CONCLUSION

SUMMARY
• Machine learning is a branch of artificial intelligence.
• Recommendation systems analyze user preferences.
• Neural networks are widely used in modern AI applications.

## Project Structure
document-summarizer-nlp
│
├── summarizer.ipynb
├── summarizer.py
├── README.md

## Achievements
**2nd Place – AI Hackathon (College Level)**  
Project: Document Summarization using NLP.

## Future Improvements
- Support scanned PDFs 
- Chapter-wise summarization
- Web interface for uploading documents
- Keyword extraction and highlighting

## Author

**Balla Saran Pyari**
