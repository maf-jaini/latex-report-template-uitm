# 📄 Universal Academic Report & Cover Page Template

<!-- BADGES SECTION -->
[![Open in Overleaf](https://img.shields.io/badge/Overleaf-Open%20as%20Template-008080?style=for-the-badge&logo=overleaf&logoColor=white)](https://www.overleaf.com/read/qzgsrrrnqvzm#0ea510)
[![LaTeX Version](https://img.shields.io/badge/LaTeX-pdfLaTeX-005fa6?style=for-the-badge&logo=latex&logoColor=white)](https://www.latex-project.org/)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey?style=for-the-badge)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub Stars](https://img.shields.io/github/stars/mafjaini/YOUR_REPO_NAME?style=for-the-badge&color=gold)](https://github.com/mafjaini/YOUR_REPO_NAME/stargazers)

---

A highly modular, professional LaTeX template designed for university assignments, mini-reports, and academic papers. This template abstracts complex formatting and styling into dedicated engine files, allowing you to focus entirely on writing your report content and filling in your assignment details.

Created originally for Universiti Teknologi MARA (UiTM) students, but easily adaptable for any institution.

## 🚀 Quick Start

### Option 1: Use on Overleaf (Recommended)
Click the badge above or [Open on Overleaf](https://www.overleaf.com/read/qzgsrrrnqvzm#0ea510) to instantly clone this template into your Overleaf account.

### Option 2: Local Use (LaTeX Editor / VS Code)
1. Clone this repository: `git clone https://github.com/mafjaini/your-repo-name.git`
2. Open `main.tex` in your LaTeX editor (e.g., TeXstudio, VS Code with LaTeX Workshop).
3. Compile using **pdfLaTeX**.

## ✨ Features

* **Modular Architecture:** Deep LaTeX configurations are safely hidden in `.sty` files to prevent accidental breakage.
* **Centralized Configuration:** Edit all your assignment details (course code, student IDs, lecturer name) in one single file (`config.tex`).
* **Automated Cover Page:** Beautiful, balanced cover page that auto-generates based on your configuration data.
* **Dynamic Watermarks:** Supports different transparent watermark logos for the cover page and the main content pages.
* **Custom Color Palette:** Built-in professional colors (`blue`, `purple`, `darkgray`) for academic branding.

## 📂 File Structure

This project uses a "Separation of Concerns" methodology:

```text
my-report-project/
│
├── main.tex                       # The master driver file (compile this!)
│
├── styles/                        # Internal Engines (Do not edit for daily use)
│   ├── core.sty                   # Core packages, geometry, and color definitions
│   └── author.sty                 # Permanent author metadata and template license
│
└── subfiles/                      # Layout & Content
    ├── config.tex                 # ✏️ Edit this: Course, students, and assignment data
    ├── header_footer.tex          # Page headers and footers setup
    ├── title_pages_watermark.tex  # Large cover page watermark logic
    ├── pages_watermark.tex        # Standard page watermark logic
    ├── titlepage.tex              # Cover page structural layout
    ├── colophon.tex               # The colophon (Version, License Disclaimers)
    ├── intro.tex                  # Section: Introduction
    ├── linear.tex                 # Section: Methodology / Content
    └── appendix.tex               # Section: Appendices
```

## ⚖️ License

This project is licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)**. 

You are free to use, modify, and distribute this template for both personal and commercial academic purposes. See the `LICENSE` file for more details.

---
*Developed by M.A.F Jaini (2026)*

If you found this template helpful, please consider giving this repository a ⭐️ on GitHub to help other students find it!
