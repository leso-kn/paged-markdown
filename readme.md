[![Online Demo](https://img.shields.io/static/v1?label=Demo&message=View%20in%20Browser&color=blue)](https://lesosoftware.com/paged-markdown-demo)

# Paged Markdown

Paged Markdown (or `paged.md` for short) is a modern approach to creating slide-based presentations.

Besides presentations, there is also a dialect for creating text documents with multiple pages (paper, essay, etc.) on [this branch](https://github.com/leso-kn/paged-markdown/tree/text-document).

## About

As the name suggests, `paged.md` is based on [Markdown](https://daringfireball.net/projects/markdown/).

Unlike with classical presentation software, there's no official editor for creating slides (though [Visual Studio Code](https://code.visualstudio.com/) is recommended). In fact, any text editor can be used to create and edit Paged Markdown presentations.

The result can be displayed (presented) in any modern browser at any stage of the creation process, meaning there's no need to convert or render anything between editing and presenting (presentation files already have the .htm file extension).

## Getting started

For editing, it is recommended to use [Visual Studio Code](https://code.visualstudio.com/), since it provides a variety of features to edit Markdown documents.

1. Download or clone this repository
2. Rename the folder to the desired name of your presentation
3. Open the folder in Visual Studio Code
   * Alternatively: Open `presentation.htm` in any text editor of your choice

### Quick tutorial

* To preview or display your presentation, open it inside any modern browser (Firefox, Chrome etc.)
* In Visual Studio Code, you can use the Markdown Preview feature directly
* Use regular Markdown to create your presentation
* As usual with Markdown, HTML can be used as well in the entire document
  * This allows for more flexible formatting
* Slides are arranged inside `<page>` tags

> To switch between slides in Visual Studio Code, edit the number inside `page:nth-of-type(...)` in the `<style>` tag in the very end of your `presentation.htm`.

### Design

You can change colors and adjust / extend the design of your slides by customizing `design.css` to your needs and taste.

There is also `logic.css`. Feel free to look around in here too, this file is supposed to handle the more generic slide design like animations and the base definition of a `<page>` (slide) tag.

## FAQ

### Visual Studio Code

**`"Some content has been disabled in this document"`**

By default, the Markdown preview of Visual Studio Code blocks external urls.

This is actually a really handy behaviour in the case of `paged.md`: The javascript logic, that provides keybindings and markdown rendering inside the web browser, is not needed during editing.

Since it is loaded from an external server ([link](https://lesosoftware.com/paged.md)), Code automatically prevents the script from being executed.

The warning itself can just be hidden by clicking on it and selecting _'Disable preview security warning in this workspace'_.

## Limitations

A common usecase with slides is to export them to the pdf format.

This _is_ possible with Paged Markdown presentations, but the way to do it at the moment is not exactly beautiful:

To convert your slides to pdf, simply open the presentation in your web browser and navigate to the first slide. Press `CTRL+P` to print the current page and select "Save to PDF". You will need to repeat this step for each slide (for filenames, choose a new folder and put something like `01.pdf`, `02.pdf`, `...`).

After saving all slides, you can use any PDF-merge tool to combine the files into a single pdf document. On Linux, there's also the `pdfunite` utility, that can be used for this. Nevertheless, this is certainly not a nice way to do it.

---

Paged Markdown – Copyright (c) Lesosoftware 2021
