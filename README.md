# VULNERABILITY ANALYSIS - FOOTPRINTING AND RECONNAISSANCE

## 📌 Overview

This project focuses on performing passive footprinting techniques to analyze files and identify hidden or sensitive information using various tools. The objective is to understand how data can be exposed through metadata and file analysis.

---

## 🛠️ Tools Used

* ExifTool (metadata extraction)
* Hex Editor (binary analysis)
* Strings (text extraction)
* Binwalk (hidden file detection and extraction)
* File command (file type identification)

---

## 🔍 Analysis Summary

### 1. Metadata Extraction (ocean.jpg)

* Hidden information was found in the metadata.
* Demonstrates that sensitive data can be stored invisibly within files.

### 2. Hex Analysis (computer.jpg)

* Raw binary data was analyzed.
* Shows that files contain structured data beyond what is visible.

### 3. Strings Extraction (computer.jpg)

* Readable strings such as "JFIF" and "ICC_PROFILE" were found.
* Indicates embedded information within the file.

### 4. Hidden Data Detection (dog.jpg)

* Binwalk detected an embedded ZIP file.
* A hidden file (`hidden_text.txt`) was successfully extracted.
* Demonstrates steganography techniques.

### 5. File Type Analysis

* `solitaire.exe` → identified as PNG image (disguised file)
* `rubiks.jpg` → identified as PNG image (misleading extension)

---

## ⚠️ Key Findings

* Files can contain hidden data without visible signs.
* File extensions can be manipulated to disguise actual file types.
* Metadata can expose sensitive information.
* Specialized tools are required to uncover hidden content.

---

## 👤 Author

**Lyana Yasmin**
