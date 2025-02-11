# 📄 PDF to Searchable Text Evaluation

🚀 **Evaluate frameworks for converting PDFs into searchable text using a Gradio app.** Upload a PDF and optionally provide ground truth images, text, or tables for benchmarking extraction results.


## ⚖️ Frameworks Compared
📌 **PyMuPDF** – Fast text & image extraction  
📌 **Tesseract** – OCR-based, best for scanned PDFs  
📌 **PyPDF** – Basic text extraction, lacks formatting retention  
📌 **Camelot** – Best for tabular data extraction  
📌 **PDFMiner** – Powerful text extraction with layout analysis  
📌 **PDFPlumber** – Structured data extraction, including tables & images  


## 📊 Key Metrics
✅ **Text Accuracy** – How well text is extracted  
✅ **Table Detection** – Table extraction accuracy  
✅ **Image Preservation** – Retention of embedded images  
✅ **Format Retention** – Maintenance of document structure  
✅ **Processing Time** – Speed of extraction  


## 🛠️ Feature Comparison
| Feature              | PyMuPDF | PDFPlumber | Tesseract | PDFMiner | PyPDF | Camelot |
|----------------------|---------|------------|-----------|----------|-------|---------|
| 📄 **Text Extraction** | ✅      | ✅         | ✅        | ✅       | ✅    | ❌      |
| 🏛️ **Table Extraction** | ✅      | ✅         | ❌        | ❌       | ❌    | ✅      |
| 🖼️ **Image Extraction** | ✅      | ✅         | ❌        | ✅       | ✅    | ❌      |
| 📑 **Scanned PDFs Support** | ✅ (OCR) | ✅ (OCR) | ✅       | ❌       | ❌    | ❌      |


## 🎯 Summary
- ⚡ **PyMuPDF** is fast and efficient.  
- 📜 **Tesseract** is best for scanned PDFs.  
- 📊 **Camelot** excels at table extraction.  
- 🏗 **PDFPlumber & PDFMiner** provide detailed structure.


## 🚀 How to Use
1️⃣ Clone the repo: `git clone <repo-url>`  

2️⃣ Run the app: `Evaluation_pdf_to_text.ipynb` 

3️⃣ Upload PDF and run the gradio app to get the results



## 🔗 References
🔹 [PyMuPDF](https://github.com/pymupdf/PyMuPDF)  
🔹 [Tesseract OCR](https://github.com/tesseract-ocr/tesseract)  
🔹 [PDFMiner](https://github.com/pdfminer/pdfminer.six)  
🔹 [PDFPlumber](https://github.com/jsvine/pdfplumber)  
🔹 [Camelot](https://github.com/camelot-dev/camelot)  

