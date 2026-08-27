# Quarto Resume / CV Template

A clean, professional, and ATS-friendly resume and CV template built using **Quarto Markdown**, Font Awesome icons, and custom print-optimized CSS. It allows you to write your CV in plain Markdown and compile it into a polished HTML page designed for crisp, clean PDF export.

---

## 🚀 Key Features

* **Markdown-First Workflow:** Write and update your experience, education, and projects effortlessly using plain Markdown syntax without messing with complex LaTeX or graphical design tools.
* **Print-Optimized CSS (`styles.css`):** Features custom print media rules (`@page`, margins, font sizes, floating date alignments) engineered specifically to export a flawless 1- or 2-page PDF straight from your browser.
* **Built-in Font Awesome Integration:** Seamlessly use modern icons for phone numbers, locations, emails, LinkedIn, GitHub, and external project links via Quarto shortcodes.
* **Responsive HTML Output:** Compiles into a clean web page that can also double as a web-accessible digital CV.

---
## 🖨️ How to Compile and Export to PDF

After you make your relevant changes in `cv.qmd` for each section,
run the following command in your terminal within the project directory to render the HTML `cv.html`, then you can use your browser to view or print it to pdf if you desire.

```bash
quarto render cv.qmd --to html
```
---

## 📂 Project Structure

```text
cv-template/
├── cv.qmd        # Main Quarto source file containing your resume content
├── styles.css       # Custom print and layout styling (margins, typography, grid)
├── _quarto.yml      # Quarto project configuration (optional)
└── assets/          # (Optional) Profile images, icons, or compiled outputs
