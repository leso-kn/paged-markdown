[![Online Demo](https://img.shields.io/static/v1?label=Demo&message=View%20in%20Browser&color=blueviolet)](https://lesosoftware.com/paged-markdown-doc-demo.pdf)

# ⭐️ Update

[Paged Markdown 3](https://github.com/leso-kn/paged-markdown-3) is the latest version of the Paged Markdown document format for scientific writing. It comes with a simplified syntax, lots of improvements and new features.

# Paged Markdown

_This is version 1 of the document format. It is still suitable for [creating slide based presentations](https://github.com/leso-kn/paged-markdown). For scientific writing however, Paged Markdown 3 is recommended (see the above message)._

## \> Text Document Flavor

This branch contains a lightweight dialect of Paged Markdown, specialized for creating text documents with multiple pages (paper, essay, etc.).

Check out the [main branch](https://github.com/leso-kn/paged-markdown) if you're interested in creating slide-based presentations in Markdown.

## About

This is a small extension for the [Markdown](https://daringfireball.net/projects/markdown/) language.

Based on a single css stylesheet, it adds the ability to control page breaks in Markdown documents and provides a bunch of new elements that are common in essays and scientific papers (foot notes, table of contents, title page etc.).

Just like any regular Markdown document, the result can be converted to HTML and PDF (see the [Printing and PDF export](#printing-and-pdf-export) section below).

## Getting started

For editing, it is recommended to use [Visual Studio Code](https://code.visualstudio.com/), since it provides a variety of features to edit Markdown documents.

1. Download or clone this repository
2. Rename the folder to the desired name of your presentation
3. Open the folder in Visual Studio Code
   * Alternatively: Open `document.md` in any text editor of your choice

### Reference

The initial [document.md](document.md) contains a quick feature reference.

### Design

Because this flavor of Paged Markdown is much more lightweight than the version for presentations, it was decided to put all design- and layout definitions into a single CSS file: `doc.css`. It contains typography settings, page layout and definitions of custom elements.

You can customize and extend this file to your needs and taste.

## Printing and PDF export

It is usually very easy to print Paged Markdown documents, or to export them as PDF, using a Markdown capable editor.

For example, in [Visual Studio Code](https://code.visualstudio.com/), it is possible to convert Markdown documents to HTML using the [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) extension. The HTML file can then be opened in any modern browser like Firefox or Chrome, where you can use the "Print Page" function, to print the document, or save it as PDF file.

Manual page breaks you defined in your document should be considered and displayed by the print preview of the web browser.

---

Paged Markdown – Copyright (c) Lesosoftware 2021
