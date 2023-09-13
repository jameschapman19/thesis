Here is a possible readme for your PhD thesis template:

# Thesis

This is a LaTeX template for writing a PhD thesis. It follows the guidelines of the University of London and provides a clear structure and formatting for your document.

## Set-up

To use this template, you need to have a LaTeX distribution installed on your computer. You can download and install [TeX Live], which is a comprehensive and cross-platform LaTeX system.

You also need to have a code editor that supports LaTeX syntax and features. We recommend using [Visual Studio Code], which is a free and open-source code editor with many extensions and customizations.

To set up Visual Studio Code for LaTeX, follow these steps:

- Install the [LaTeX Workshop] extension, which provides many useful features for editing and compiling LaTeX documents.
- Install `latexmk` from TeX Live (https://tug.org/texlive/)

- Configure the LaTeX Workshop extension to use `latexmk` as the default recipe. You can do this by adding the following lines to your `settings.json` file:

## Version Control/Using with Overleaf when you want

You can switch back and forth between editing your thesis locally and on Overleaf. To do this, you just host your thesis on GitHub and use Overleaf's [GitHub integration] to sync your changes. Wahey!


## Hints

- Use `textwrap` in the Visual Studio Code settings to wrap text when writing. You can do this by adding the following line to your `settings.json` file:

```json
"editor.wordWrap": "on"
```

- Use the `\input{filename}` command to include other files in your main document. This helps you organize your content into smaller and manageable chunks.
- Use the `\cite{key}` command to cite references from your `bibliography.bib` file. You can use a tool like [Zotero] to manage your references and export them to BibTeX format.
- Use the `\ref{label}` command to refer to figures, tables, sections, etc. that you have labeled with the `\label{label}` command. This ensures that the references are updated automatically if you change the order or number of your elements.
- Use the `\gls{term}` command to use terms from your `glossary.tex` file. This helps you define and use consistent terminology throughout your document.
- Use the `\todo{note}` command to insert notes and comments in your document. This helps you keep track of what you need to do or revise later.