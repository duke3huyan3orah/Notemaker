
# 📄 PDF Note Maker

A lightweight **browser-based PDF tool** that lets you upload PDFs, select pages, apply filters, rearrange pages, and export a custom combined PDF.

Everything runs **locally in your browser**, so your PDFs are never uploaded anywhere.

---

## ✨ Features

- 📂 **Upload multiple PDF files**
- 📑 **Select or deselect pages**
- 🔀 **Drag and reorder pages**
- 🎨 **Apply visual filters**
  - **Grayscale**
  - **Invert**
  - **Brightness**
  - **Contrast**
  - **Saturation**
- 📐 **Multiple layout options**
  - **1 page per sheet**
  - **2 pages per sheet**
  - **4 pages per sheet**
  - **6 pages per sheet**
- ✂ **Auto-crop white margins**
- 📄 **Export a clean combined PDF**
- 🖥 **Runs completely in the browser**

---

## 🖼 Interface

The tool provides:

- Drag-and-drop **PDF upload**
- **Page preview grid**
- **Filter control sidebar**
- **Layout and export options**

You can visually select pages and preview filter changes before exporting.

---

## 🛠 Technologies Used

- **HTML**
- **CSS**
- **JavaScript**
- **PDF.js** – Rendering PDF pages
- **pdf-lib** – Creating and exporting PDFs

External libraries used:

```html
https://cdnjs.cloudflare.com/ajax/libs/pdf.js/3.11.174/pdf.min.js
https://cdnjs.cloudflare.com/ajax/libs/pdf-lib/1.17.1/pdf-lib.min.js
```

---

## 🚀 How to Use

1. Open the HTML file in your browser.
2. Click **Add PDFs** or drag PDFs into the drop zone.
3. Select or deselect the pages you want.
4. Drag pages to **reorder them**.
5. Apply filters or change layout if needed.
6. Click **Export PDF**.

The tool will generate:

```
notes.pdf
```

---

## ⚙️ Installation

No installation required.

Simply download the project and open:

```
pdf_note_maker.html
```

in any modern browser.

---

### Optional: Run with a Local Server

You can also run it with a simple server:

```bash
python -m http.server
```

Then open:

```
http://localhost:8000
```

---

## 📁 Project Structure

```
pdf-note-maker
│
├── pdf_note_maker.html
└── README.md
```

---

## 🔒 Privacy

All processing happens **locally in your browser**.

Your PDFs **are never uploaded or stored on any server**.

---

## 🧠 Possible Future Improvements

- Page rotation
- OCR support
- Annotations
- Dark mode
- Export pages as images
- Page splitting

---

## 📜 License

This project is released under the **MIT License**(just a joke).
