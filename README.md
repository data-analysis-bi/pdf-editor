# 📄 Private PDF Pro

> **All PDF Tools in One Place — 100% Offline & Private**  
> Your files never leave your device. No uploads. No accounts. No internet required.

🔗 **Live Demo:** [[data-analysis-bi.github.io/pdf-editor](https://data-analysis-bi.github.io/pdf-editor/)](https://data-analysis-bi.github.io/)

---

## ✨ Features

| Tool | Description |
|------|-------------|
| 🔗 **Merge PDF** | Combine multiple PDF files into one document |
| ✂️ **Split PDF** | Extract pages or split a PDF into multiple files |
| 🗜️ **Compress PDF** | Reduce file size while keeping quality |
| 🖼️ **PDF to Image** | Convert PDF pages to PNG or JPG images |
| ⚡ **Batch Processing** | Apply operations to multiple files at once |

---

## 🔒 Privacy First

This app runs **entirely in your browser**. No files are ever uploaded to any server. Everything is processed locally using:
- [PDF.js](https://mozilla.github.io/pdf.js/) — PDF rendering
- [Tesseract.js](https://tesseract.projectnaptha.com/) — OCR support

---

## 🚀 Running Locally

**Requires Python:**
```bash
# Navigate to the project folder and run:
python -m http.server 8080
```
Then open your browser and go to: [http://localhost:8080](http://localhost:8080)

---

## 📁 Project Structure

```
pdf-editor/
├── index.html          # Main entry point
├── manifest.json       # Web app manifest (PWA support)
├── asset-manifest.json # Asset map
└── static/
    └── js/
        ├── bundle.js                         # Main application bundle
        ├── vendors-node_modules_pdfjs-dist_build_pdf_mjs.chunk.js
        └── vendors-node_modules_tesseract_js_src_index_js.chunk.js
```

---

## 🛠️ Tech Stack

- **Frontend:** React (compiled/bundled)
- **PDF Engine:** PDF.js
- **OCR Engine:** Tesseract.js
- **Hosting:** GitHub Pages

---

## 📜 License

This project is for personal and educational use.
