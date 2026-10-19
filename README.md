# ⚖️ PhiloNotes — Philosophy of Law Reader & Reviewer

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live%20Web%20App-success?logo=github)](https://astuarte.github.io/PhiloNotes/)
[![Course](https://img.shields.io/badge/Subject-Philosophy%20of%20Law-amber)](https://github.com/Astuarte/PhiloNotes)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

An elegant, high-performance web reader and legal review companion for **Philosophy of Law** (covering Dean David Robert C. Aquino's textbook *Philosophy of Law*, Chapters 1 to 3, plus class reviewers, case briefs, and lecture notes).

> 🌐 **Live Web Application:** [https://astuarte.github.io/PhiloNotes/](https://astuarte.github.io/PhiloNotes/)

---

## 🚀 How to Enable GitHub Pages (Hosting Guide)

Because the repository is formatted with `index.html` and `.nojekyll` at the root, hosting it on GitHub is completely free and takes less than a minute:

1. Go to your repository on GitHub: **[github.com/Astuarte/PhiloNotes](https://github.com/Astuarte/PhiloNotes)**
2. Click on the **Settings** tab (the gear icon near the top right).
3. In the left-hand sidebar, under **Code and automation**, click **Pages**.
4. Under **Build and deployment**:
   - **Source**: Select `Deploy from a branch`
   - **Branch**: Select `main`
   - **Folder**: Select `/ (root)`
5. Click **Save**.
6. Wait 1–2 minutes. GitHub will display a notification with your live site URL:
   ```text
   Your site is live at https://astuarte.github.io/PhiloNotes/
   ```

---

## ✨ Features

- 🏛️ **Curated Law Library Themes:**
  - **Parchment Theme (Default):** Classic cream aesthetic designed for long, comfortable study sessions.
  - **Midnight Dark Mode:** Low-light slate theme for late-night bar exam and midterm reviews.
  - **Editorial Light:** High-contrast crisp white paper layout.
- 🔤 **Typography & Font Scaling:**
  - Toggle between **Serif** (*Merriweather*) and **Sans-Serif** (*Inter*).
  - Instant scaling buttons (`A-` / `A+`) for personalized reading comfort.
- 📑 **Interactive Table of Contents & ScrollSpy:**
  - Auto-generated hierarchical navigation derived from document headings.
  - Real-time scroll indicator tracking your current reading location.
- 🔍 **Instant Full-Text In-Document Search:**
  - Real-time matching with automatic scroll-to-result for doctrines, statutory articles, and jurisprudence.
- 📋 **1-Click Case Citation Copying:**
  - Click on any landmark case name (*e.g., Alonzo v. IAC, Angara v. Electoral Commission, Luego v. CSC*) to automatically copy the citation to your clipboard.
- 📂 **Bundled Syllabi & Custom File Support:**
  - Preloaded with comprehensive summaries and structured reviewers.
  - Supports dragging and dropping or opening any local `.md` or `.txt` file into the reader on the fly.
- 🖨️ **Print & PDF Ready:**
  - Includes a dedicated print stylesheet that strips sidebars, search bars, and navigation, generating clean study printouts.

---

## 📚 Bundled Materials

| Document | Description |
| :--- | :--- |
| **📘 Page-by-Page Summary (Aquino)** | Exhaustive, page-by-page breakdown of Chapters 1 to 3 (Pages 1–125), including all cited Supreme Court doctrines and epigraphs. |
| **📑 Structured Reviewer & Doctrinal Index** | Outline-style reviewer organized by doctrines, tests, definitions, and comparative matrices. |
| **🎯 Master Bar-Style Quiz & Review Companion** | Comprehensive self-testing exam covering Chapters 1 to 3 (Pages 1–125) with 6 test formats (MCQ, True/False, Identification, Matching, Comparative Matrices, Bar Problems) with instant click-to-reveal answers. |
| **📝 Chapter 1 Notes** | In-depth notes focusing on the nature of law, philosophy, separation of powers, and constitutional commissions. |
| **🎓 Class Lecture Notes (Sept. 2026)** | Practical class notes, case discussions, and professor highlights. |

Raw Markdown (`.md`), Word (`.docx`), and textbook reference files are preserved in the [`Documents/`](file:///c:/Users/gapple3c/OneDrive/Desktop/School%20of%20Law%20Programs%20for%20Sharing%20Files/PhiloNotes/Documents) folder.

---

## 📁 Repository Structure

```text
PhiloNotes/
├── index.html              # Primary GitHub Pages web application entrypoint
├── PhiloNotes_Reader.html   # Standalone web reader
├── README.md               # Documentation and setup instructions
├── .nojekyll               # Bypasses Jekyll to serve assets directly
├── .gitignore              # Ignores temporary OS and Office lock files
└── Documents/              # Original source documents and notes
    ├── Aquino_Chapter_1_Summary_and_Reviewer.md
    ├── Aquino_Philosophy_of_Law_Comprehensive_Quiz.md
    ├── Aquino_Philosophy_of_Law_Page_By_Page_Summary.md
    ├── Aquino_Philosophy_of_Law_Structured_Reviewer.md
    ├── CHAPTER-1.docx
    ├── CHAPTER-1.md
    ├── Chapter1toChapter3_Aquino.md
    ├── Chapter1toChapter3_Aquino.pdf
    ├── HISPHI020-Notes-Sept.-21-2026.docx
    ├── HISPHI020-Notes-Sept.-21-2026.md
    ├── Lecture_Notes_HISPHI020_Summary_and_Reviewer.md
    └── PhiloNotes_Reader.html
```

---

## 💻 Running Locally / Offline

No build steps, package managers, or local web servers are required. Simply:
1. Clone or download this repository.
2. Double-click [index.html](file:///c:/Users/gapple3c/OneDrive/Desktop/School%20of%20Law%20Programs%20for%20Sharing%20Files/PhiloNotes/index.html) or [PhiloNotes_Reader.html](file:///c:/Users/gapple3c/OneDrive/Desktop/School%20of%20Law%20Programs%20for%20Sharing%20Files/PhiloNotes/PhiloNotes_Reader.html) in your browser of choice (Chrome, Edge, Firefox, Safari).

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
| :--- | :--- |
| <kbd>Ctrl</kbd> + <kbd>B</kbd> / <kbd>Cmd</kbd> + <kbd>B</kbd> | Toggle Table of Contents Sidebar |
| <kbd>Ctrl</kbd> + <kbd>F</kbd> / <kbd>Cmd</kbd> + <kbd>F</kbd> | Focus Document Search Bar |
| <kbd>Ctrl</kbd> + <kbd>P</kbd> / <kbd>Cmd</kbd> + <kbd>P</kbd> | Print / Export Clean PDF Notes |
