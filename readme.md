# Thesis ✍️

This is a LaTeX template for writing a PhD thesis 🎓. It follows the guidelines of the University of London and provides a clear structure and formatting for your document.

## Set-up 🔧

To use this template, you need to have a LaTeX distribution installed on your computer. You can download and install [TeX Live], which is a comprehensive and cross-platform LaTeX system.

You also need to have a code editor that supports LaTeX syntax and features. We recommend using [Visual Studio Code 💻], which is a free and open-source code editor with many extensions and customizations.

To set up Visual Studio Code for LaTeX, follow these steps:

- Install the [LaTeX Workshop] extension, which provides many useful features for editing and compiling LaTeX documents.
- Install `latexmk` from TeX Live (https://tug.org/texlive/)

**Extra Tips**: 
- To avoid tracking unnecessary files, consider adding the standard LaTeX `.gitignore` file to your repo. Grab it from [here](https://github.com/github/gitignore/blob/main/TeX.gitignore) 🚫.
- For easy collaboration and synchronization, check out the [GitHub Synchronization with Overleaf](https://www.overleaf.com/learn/how-to/GitHub_Synchronization) 🔄.

## Hints 💡

- Use `textwrap` in the Visual Studio Code settings to wrap text when writing. You can do this by adding the following line to your `settings.json` file:

```json
"editor.wordWrap": "on"
```

- Use the \input{filename} command to include other files in your main document. This helps you organize your content into smaller and manageable chunks 📄.
- Use the \cite{key} command to cite references from your bibliography.bib file. You can alos use a tool like [Zotero] to manage your references and export them to BibTeX format 📚
