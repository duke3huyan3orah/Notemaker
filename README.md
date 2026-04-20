📄 PDF Note Maker

A lightweight browser-based PDF tool that lets you upload PDFs, select specific pages, apply visual filters, rearrange pages, and export a custom combined PDF.

Built entirely with HTML, JavaScript, and client-side libraries, meaning everything runs locally in your browser — no uploads to a server.

✨ Features
📂 Upload multiple PDF files
📑 Select or deselect pages before exporting
🔀 Drag & reorder pages
🎨 Apply visual filters
Grayscale
Invert
Brightness
Contrast
Saturation
📐 Export layouts
1 page per sheet
2 pages per sheet
4 pages per sheet
6 pages per sheet
✂ Auto-crop page whitespace
📄 Export a clean combined PDF
🖥 Runs 100% in the browser
🖼 Interface Overview

The tool provides:

Drag-and-drop PDF upload
Page preview grid
Filter control sidebar
Export and layout options

You can visually select pages and instantly preview filter changes before exporting.

🛠 Technologies Used
HTML / CSS / JavaScript
PDF.js – rendering PDF pages
pdf-lib – creating and exporting PDFs

External libraries used:

https://cdnjs.cloudflare.com/ajax/libs/pdf.js/3.11.174/pdf.min.js
https://cdnjs.cloudflare.com/ajax/libs/pdf-lib/1.17.1/pdf-lib.min.js
🚀 How to Use
Open the HTML file in your browser.
Click Add PDFs or drag PDFs into the drop zone.
Select or deselect pages.
Reorder pages by dragging them.
Adjust filters or layout options if needed.
Click Export PDF.

The tool will generate a file called:

notes.pdf
⚙️ Installation

No installation required.

Simply download the HTML file and open it:

pdf_note_maker.html

Or host it with any static server.

Example:

python -m http.server

Then open:

http://localhost:8000
📁 Project Structure
pdf-note-maker
│
├── pdf_note_maker.html
└── README.md
🔒 Privacy

All processing happens locally in your browser.
Your PDFs are never uploaded to any server.

🧠 Possible Future Improvements
Rotate pages
OCR support
Annotation tools
Dark mode
Export to images
Page splitting
📜 License

MIT License

If you want, I can also make a much cooler GitHub README with badges, screenshots, and demo GIFs so the repo looks 10× more professional.
