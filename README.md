<div align="center">

# LaTeX Software Engineering Resume Template

[![LaTeX](https://img.shields.io/badge/LaTeX-TeX%20Live-008080?style=for-the-badge&logo=latex&logoColor=white)](https://www.latex-project.org/)
[![Document Class](https://img.shields.io/badge/Document%20Class-resume.cls-blue?style=for-the-badge)](resume.cls)
[![ATS Friendly](https://img.shields.io/badge/Format-ATS%20Optimized-success?style=for-the-badge)](main.tex)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)

**The version-controlled LaTeX source code and custom typesetting styling class for Aniket Yadav's software engineering resume.**

</div>

---

## 1. Overview

This repository maintains the version-controlled LaTeX source code for my professional developer resume. Built with a custom modular document class (`resume.cls`), the layout optimizes ATS (Applicant Tracking System) parseability, typographic balance, and single-page density.

---

## 2. Repository Structure

```
resume_latex/
├── resume.cls              # Custom LaTeX document class with typography styling
├── main.tex                # Master resume source content and structure
├── Annii_RESUME (1).pdf    # Pre-compiled high-resolution PDF document
└── README.md               # Repository documentation and build instructions
```

---

## 3. Typographic & Architectural Features

- **ATS Compliance:** Clean linear text stream without nested tables, text boxes, or non-standard font encodings.
- **Modular Macro Definitions:** Custom environments for projects, technical skills matrices, and educational timelines.
- **Vector Iconography & Links:** High-fidelity hyperlinked social handles and project repositories.
- **Single-Page Optimization:** Tight margin geometry and proportional leading ensuring comprehensive coverage on a single page.

---

## 4. Compilation Instructions

### Local Compilation via TeX Live / MiKTeX
```bash
# Ensure pdflatex is installed
pdflatex main.tex
```

### Online Compilation via Overleaf
1. Create a new blank project in [Overleaf](https://www.overleaf.com/).
2. Upload `main.tex` and `resume.cls`.
3. Set the compiler to **pdfLaTeX** and compile.
