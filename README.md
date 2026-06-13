# Cyber Nate — PDF Document Intelligence Suite

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![GitHub Pages](https://img.shields.io/badge/Deployed-GitHub%20Pages-brightgreen)](https://yourusername.github.io/cybernate-pdf-suite/)

A privacy-first, client-side document processing platform. No server. No uploads. Your files never leave your browser.

**[Live Demo →](https://yourusername.github.io/cybernate-pdf-suite/)**

---

## Features

### Free Tier
- **OCR Text Extraction** — Extract text from scanned PDFs using Tesseract.js (20+ languages)
- **Word Document Conversion** — Convert PDFs to editable `.docx` with page breaks
- **Image Extraction** — Pull all embedded images from PDFs as a ZIP download
- **Batch Processing** — Process multiple PDFs simultaneously
- **Page Range Selection** — Process only pages 3–7 of a 200-page document
- **Find & Replace** — Clean up OCR output before exporting
- **Live Stats** — Character count, word count, page count in real-time

### Pro Tier (Coming Q3 2026)
- AI Document Summarization (Claude API)
- Ask Your Document — Q&A chat with contracts, briefs, reports
- Searchable PDF Output — render scanned PDFs with text layer
- OCR Confidence Scoring — flag low-confidence words in red
- Multi-format export — `.txt`, `.docx`, `.md`, `.csv`

---

## Why This Exists

Most PDF tools upload your documents to remote servers. For legal, medical, and government documents, that's a non-starter.

Cyber Nate runs entirely in your browser using:
- **PDF.js** — PDF rendering and text extraction
- **Tesseract.js** — OCR engine (pure JavaScript, no backend)
- **docx.js** — Word document generation
- **JSZip** — ZIP file creation for image downloads

Your files are processed locally. Nothing is transmitted.

---

## Use Cases

| Industry | Use Case |
|----------|----------|
| **Legal** | Digitize scanned contracts, court filings, discovery documents |
| **Compliance** | Convert regulatory filings (FIRS, CAC, NCC) to editable formats |
| **Government** | Archive incident reports, police records, evidence documents |
| **Academia** | Extract text from scanned journals, theses, research papers |
| **Healthcare** | Process scanned medical records (HIPAA-compliant, client-side) |

---

## Quick Start

No build step. No dependencies to install.

```bash
# Clone the repo
git clone https://github.com/yourusername/cybernate-pdf-suite.git

# Open directly in browser
cd cybernate-pdf-suite
open index.html
