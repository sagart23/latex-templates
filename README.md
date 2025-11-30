# 📘 LaTeX Templates for ICSE & ISC (Class 10 & 12) — Exams, Notes & Worksheets

This repository contains a curated collection of **LaTeX templates** used for creating:

- **80-marks ICSE & ISC examinations** (Class 10 and 12)  
- **Unit tests, slip tests & full-length papers**  
- **Articles and academic documents**  
- **Notes, practice sets & worksheets**  
- **Custom `.sty` style packages and formatting tools**  

These templates are designed for **teachers, tutors, and schools** who want clean, consistent, professional-quality documents with minimal effort.

---

## 📁 Repository Structure

This repository now includes **two kinds of templates**:

### **1️⃣ Legacy Templates (Full Preamble Included)**  
Complete `.tex` files with the entire preamble written inside.  
These are suitable for quick one-file usage.

### **2️⃣ Modular Templates (Recommended)**  
New cleaner templates that load modular `.sty` files such as:

```latex
\usepackage{sagar-boxes}
\usepackage{macros}
````

This structure keeps your documents organized and makes updates easy.
All style files are stored in the **`styles/`** folder.

### **Folder Layout**

```
latex-templates/
│
├── legacy-templates/
│   └── (Older full-preamble exam, worksheet, and note files)
│
├── modular-templates/
│   ├── ICSE-80marks-template.tex
│   ├── ISC-80marks-template.tex
│   ├── worksheet-template.tex
│   └── notes-template.tex
│
├── styles/
│   ├── sagar-boxes.sty
│   └── macros.sty
│
└── README.md
```

---

## 🚀 Features

* 📄 **Exam templates** for ICSE (10) and ISC (12) — standard 80-marks pattern
* ✍️ **Article templates** with clean typography
* 📝 **Notes & worksheet layouts** for everyday classroom use
* 🎨 **Custom `.sty` files** for boxes, highlights, formatting, and math environments
* 📂 Clean and organized folder structure
* 🔧 Fully compatible with **TeX Live, MiKTeX, Overleaf, VS Code + LaTeX Workshop, and Neovim**

---

## 🛠️ How to Use

### **1. Clone the repository**

```bash
git clone https://github.com/<your-username>/<your-repo>.git
```

---

### **2. Open in any LaTeX editor**

Compatible with:

* Overleaf
* VS Code (LaTeX Workshop)
* Neovim (VimTeX or LaTeX plugins)
* TeXShop / TeXworks
* MiKTeX & TeX Live distributions

---

### **3. Compile**

Use:

```bash
pdflatex <filename>.tex
```

or

```bash
xelatex <filename>.tex
```

Depending on the font or template.

---

## ⭐ Use Cases

Perfect for:

* Teachers preparing **ICSE/ISC question papers**
* Creating revision notes & study material
* Making worksheets with consistent branding
* Students writing technical or academic articles

---

## 🤝 Contribution

Pull requests are welcome!

You may:

* Improve templates
* Add new layouts
* Fix bugs in `.sty` files
* Suggest enhancements

---

## 🙌 Acknowledgements

Created and maintained by **Sagar Tamhankar**,
for educators who value clean, beautiful, and structured LaTeX documents.
Just tell me!
```
