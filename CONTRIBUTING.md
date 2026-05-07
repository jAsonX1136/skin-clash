# Contributing to SkinClash ✨

First off, thank you for taking the time to contribute! 🧴  
Every contribution helps people protect their skin barrier without the guesswork.

This document provides guidelines for contributing to SkinClash.  
It's a lightweight project, so the process is intentionally simple.

---

## 🐛 Reporting bugs

If you find a bug, please **open an issue** and include:

- A clear title and description
- Steps to reproduce the bug
- Your browser and device (e.g., "Chrome on iPhone 15")
- Screenshot (if applicable)

Before submitting, quickly search the [existing issues](../../issues) to avoid duplicates.

---

## 💡 Suggesting enhancements

Got an idea for a new ingredient, a conflict rule, or a feature?  
Open an issue and describe:

- What you'd like to see
- Why it would be useful (a real‑life skincare scenario helps!)
- Optional: any references or data supporting the suggestion

---

## 🔧 Setting up the project locally

SkinClash is a **zero‑dependency static site**.  
No build tools, no frameworks, no package manager required.

1. **Fork the repository** and clone your fork locally.
2. The project consists of a single file: `index.html` (and optionally `style.css` / `script.js` if the code is separated in the future).
3. Open `index.html` directly in your browser – you're ready to go.

For a live preview while editing, any static file server will work:

```bash
# Using Python 3
python3 -m http.server 8000
# Then visit http://localhost:8000
