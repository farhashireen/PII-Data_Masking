# PII Data Masking

This project is designed to automatically detect and mask Personally Identifiable Information (PII) in unstructured text data using Natural Language Processing (NLP) techniques.

## 🚀 Project Overview

Data privacy is crucial for compliance with regulations like GDPR, HIPAA, and CCPA. This tool helps anonymize sensitive data by identifying PII such as:

- Names  
- Emails  
- Phone Numbers  
- Social Security Numbers  
- Addresses  
- Dates

## 🧠 Features

- Named Entity Recognition (NER) using spaCy
- Custom regex-based detection for edge cases
- Configurable masking (e.g., replace with `[REDACTED]` or hashes)
- Easy integration with text pipelines or APIs

## 🛠️ Tech Stack

- Python
- spaCy
- re (regex)

## 🧪 How to Use

1. **Clone the repository**
   ```bash
   git clone https://github.com/farhashireen/PII-Data_Masking.git
   cd PII-Data_Masking
