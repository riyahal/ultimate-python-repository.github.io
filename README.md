<div align="center">
    
# 🐍 Ultimate Python Repository 📖

> An interactive static website for learning and browsing structured Python and Tkinter programs — with syntax-highlighted code, rendered markdown guides, and a brutalist dark theme.

</div>

<p align="center">
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
    <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
    <img src="https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white" alt="Markdown">
    <img src="https://img.shields.io/badge/license-MIT-blue?style=for-the-badge" alt="MIT License">
</p>

---

## ✨ About

This website serves as a **visual, interactive documentation platform** for the [Python-Programming-and-Tkinter](https://github.com/rhalbhavi/Python-Programming-and-Tkinter) repository. Instead of browsing raw files on GitHub, you get:

- **Syntax-highlighted Python code** rendered directly from the source files
- **Rendered Markdown guides** for conceptual topics
- **Accordion sidebar navigation** with expandable folders
- **Dropdown topic menus** for jumping between subjects
- **Image embedding** for diagrams and screenshots
- **Brutalist dark UI** with scanline animations

All content is pulled live from the repository's file tree — update the repo files and the site stays in sync.

---

## 🎯 Features

| Feature | Description |
|---|---|
| **Live Code Rendering** | Python `.py` files are fetched and displayed with Prism.js syntax highlighting |
| **Markdown Rendering** | `.md` overview files are parsed with `marked` and displayed as styled HTML |
| **Nested Sidebar Navigation** | Accordion-style tree matching the repository's folder structure |
| **Topic Dropdowns** | Quick navigation via hover-reveal menus in the header |
| **URL Hash Routing** | Direct deep-linking to any subtopic or file via `#Topic:SubTopic` |
| **Flat File Flattening** | Single-file folders display inline without unnecessary nesting |
| **Responsive Layout** | Two-column desktop layout collapses to single column on mobile |
| **Brutalist Dark Theme** | Black/dark navy background, neon green accents, scanline overlay animation |

---

## 🛠️ Tech Stack

| Technology | Purpose | Badge |
|---|---|---|
| **HTML5** | Page structure and semantic markup | <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" width="100"> |
| **CSS3** | All styling (brutalist dark theme, layout, responsive design) | <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" width="90"> |
| **JavaScript (Vanilla)** | Core application logic — routing, sidebar, content fetching and rendering | <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" width="110"> |
| **Python** | `generate_manifest.py` — walks the repo and produces `tree_manifest.json` | <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" width="100"> |
| [marked.js](https://marked.js.org/) | Markdown → HTML parsing for `.md` overview files | <img src="https://img.shields.io/badge/marked.js-000000?style=for-the-badge&logo=markdown&logoColor=white" alt="marked.js" width="100"> |
| [Prism.js](https://prismjs.com/) | Python syntax highlighting for `.py` code blocks | <img src="https://img.shields.io/badge/Prism.js-1E2A3A?style=for-the-badge&logo=javascript&logoColor=white" alt="Prism.js" width="100"> |
| **`tree_manifest.json`** | Flat-array file tree used by the frontend to render the sidebar and content | <img src="https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=json&logoColor=white" alt="JSON" width="80"> |

---

## 🗂️ Project Structure

```
.
├── index.html                # Main entry point
├── style.css                 # All styling (brutalist theme)
├── script.js                 # Core logic: routing, sidebar, content rendering
├── tree_manifest.json        # File tree index (generated)
├── generate_manifest.py      # Script to regenerate tree_manifest.json
├── README.md                 # This file
├── Core Foundations.md       # Topic overview (markdown)
├── Data Structures.md        # Topic overview (markdown)
├── Control Flow.md           # Topic overview (markdown)
├── Error Handling.md         # Topic overview (markdown)
├── Tkinter.md                # Topic overview (markdown)
│
├── Keywords and Identifiers/ # Subtopic folders with .py / .md / .png files
├── Strings/
├── Lists/
├── Tuples/
├── Sets/
├── Dictionaries/
├── If-Else-Elif Statements/
├── For Loop/
├── While Loop/
├── Functions/
├── Try-Except-Finally Statements/
├── Tkinter/
└── ...
```

Each topic folder contains either:
- Single `.py` files (directly rendered with syntax highlighting)
- A `.md` file (rendered as HTML)
- Multiple files in subdirectories (shown as expandable sidebar groups)
- `.png` images (displayed inline, or embedded within markdown)

---

## 🔗 Links

- **Live Site** — [GitHub Pages](https://rhalbhavi.github.io/ultimate-python-repository.github.io/)
- **Source Repository** — [github.com/rhalbhavi/Python-Programming-and-Tkinter](https://github.com/rhalbhavi/Python-Programming-and-Tkinter)

---

## 📄 License

This project is open source under the [MIT License](LICENSE).

---

<div align="center">
    Made with 🐍 and ☕
</div>
