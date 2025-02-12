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
3️⃣ Upload PDF and run the Gradio app to get the results  

## 🛠️ Contributing
We welcome contributions from the community! If you’d like to contribute:  
📌 **Bug Reports & Issues**: Open an [issue](https://github.com/Eval-PDF/issues) if you find any bugs.  
📌 **Feature Requests**: Suggest new features via discussions or pull requests.  
📌 **Pull Requests**: Fork the repo, make changes, and submit a pull request!  

### Contribution Guidelines:
- Ensure your changes follow best practices.  
- Keep the repository structured and well-documented.  
- Respect the licenses of individual frameworks.  

## 📜 License
Eval-STT is **open-source** under the **Apache 2.0**. Use it freely and contribute to make it better! 🚀

## 📬 Contact Us
For any questions, suggestions, or feature requests, **open an issue** or reach out to the maintainers! 💡

## 🔗 References
🔹 [PyMuPDF](https://github.com/pymupdf/PyMuPDF)  
🔹 [Tesseract OCR](https://github.com/tesseract-ocr/tesseract)  
🔹 [PDFMiner](https://github.com/pdfminer/pdfminer.six)  
🔹 [PDFPlumber](https://github.com/jsvine/pdfplumber)  
🔹 [Camelot](https://github.com/camelot-dev/camelot)  
