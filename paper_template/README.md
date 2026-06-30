# EngTeX — Scientific Paper LaTeX Template

**Professional LaTeX template for scientific articles, optimised for STEM disciplines and native IEEE two-column formatting.**

Designed for researchers, PhD students, and engineers who want to produce publication-ready papers without managing LaTeX complexity from scratch. Layout, advanced math macros, code styles, diagrams, and bibliography are already perfectly configured.

---

## ✨ Features

### 🌍 Bilingual Support (ENG/ITA)

All labels (Abstract, Keywords, Theorem, Warning, etc.) switch automatically between English and Italian by changing a single word in your document class options.

### 📰 Native Two-Column Layout (IEEE Style)

The template fully supports the IEEE-style `twocolumn` option natively. The title block will automatically span across both columns, while the abstract aligns to the left column perfectly.

### 🧮 STEM & EE Math Macros

Dozens of pre-configured macros to speed up formula writing:

- **Derivatives & Integrals**: `\der{f}{x}`, `\pder{V}{t}`
- **Transforms**: `\fourier{}`, `\laplace{}`, `\ztrans{}`
- **Phasors & Complex Math**: `\fasore{V}{\theta}`, `\real{}`, `\conj{z}`
- **Linear Algebra**: `\transpose`, `\diag{}`, `\norm{x}`
- **EE-specific**: `\snr`, `\ber`, `\dBm`, `\sinc`

### 💻 Code Listings & TikZ

Dedicated syntax highlighting for VHDL, C, C++, Java, Python, and MATLAB. 
Includes built-in macros to quickly draw hardware datapaths and generic block diagrams using TikZ.

### 📐 Theorem Environments & Custom Boxes

Ready-to-use localized environments for:

* `theorem` | `lemma` | `corollary` | `proposition` | `remark`
* Custom callout boxes: `\definition{}{}`, `\note{}`, `\warning{}`, `\example{}{}`

---

## 🚀 Get the Template

EngTeX Paper is available as a professional, ready-to-use package. It includes the complete framework, a structured boilerplate for your paper sections, and a comprehensive usage manual.

👉 **[Purchase EngTeX Paper on Gumroad](*(Insert your Gumroad link here)*)**

---

## 🛠️ Quick Start

### Local installation (VS Code + MiKTeX / TeX Live)

1. Install [MiKTeX](https://miktex.org) (Windows) or [TeX Live](https://tug.org/texlive/) (Linux/macOS).
2. Install [VS Code](https://code.visualstudio.com) + **LaTeX Workshop** extension.
3. Open the downloaded folder in VS Code.
4. Edit `main.tex` to set your metadata (authors, title, affiliations).
5. Build using the standard chain: `pdflatex → biber → pdflatex → pdflatex`.

### Overleaf

1. Click **New Project → Upload Project** and upload the provided `.zip`.
2. Set your compiler to **pdfLaTeX** (Menu → Compiler).
3. Edit `main.tex` and compile twice to ensure the bibliography is built correctly.

---
*Created by [Luca G. Sansalone](https://github.com/Sansalone-LucaG)*
