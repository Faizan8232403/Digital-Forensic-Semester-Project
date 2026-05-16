NTFS File Carver – Digital Forensics Project
📌 Overview

This project presents a Python-based NTFS File Carver designed to recover deleted files from raw disk images using signature-based file carving techniques.

The tool scans disk images sector by sector and extracts files based on known file headers and footers without relying on file system metadata.

🚀 Features
Signature-based file recovery
Supports JPEG, PNG, and PDF formats
MD5 and SHA-256 hash generation
CSV and HTML forensic report generation
Command Line Interface (CLI)
Logging system for forensic tracking
🛠️ Technologies Used
Python
hashlib (for MD5 & SHA-256)
csv module
Binary file handling
📂 Input
Raw disk images (.dd, .img)
📤 Output
Recovered files
CSV report
HTML report
Log file
⚠️ Limitations
Does not recover fragmented files
Does not preserve original filenames
Limited to predefined file signatures
👨‍💻 Contributors
Muhammad Faizan Ali
Muhammad Awais Ali
🎯 Purpose

This project demonstrates core digital forensic concepts such as:

File carving
Signature analysis
Deleted data recovery
Evidence integrity verification
