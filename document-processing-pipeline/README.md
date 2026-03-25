# Document Processing Pipeline

![Language](https://img.shields.io/badge/Language-Python-blue)
![PDF](https://img.shields.io/badge/Library-PyMuPDF-orange)
![Data](https://img.shields.io/badge/Data-Pandas-yellow)
![Type](https://img.shields.io/badge/Type-Data%20Pipeline-purple)
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow)

A scalable automation pipeline for extracting structured data from PDF documents.

---

## 🧾 Overview

This project processes batches of PDF documents and converts them into structured, machine-readable formats.

It is designed to automate early-stage document handling tasks commonly found in:

- finance workflows (invoices)
- business document processing
- data ingestion pipelines
- AI / RAG systems

---

## 🚀 Core Capabilities

- 📥 Batch ingestion of PDF files
- 📄 Text extraction from documents
- 🏷 Basic document classification
- 📊 Structured JSON output per file
- 📈 Summary CSV generation
- ⚠ Error handling and logging

---

## 🔄 Processing Workflow

1. Read PDF files from an input directory  
2. Extract text and metadata  
3. Classify document type (invoice, report, etc.)  
4. Generate structured JSON output  
5. Create a summary CSV file  
6. Log processing results  

---

## 📂 Project Structure

```text
document-processing-pipeline/
  src/
    ingest.py
    extract.py
    classify.py
    export.py
    main.py
  input/
  output/
  config/
    settings.json
