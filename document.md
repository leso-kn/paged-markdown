<link rel=stylesheet href=doc.css>

# The Topic

## Subtitle of the topic

<info>

<!-- This is an invisible comment. &#9; is a html escape sequence for the 'tab' character -->

**Author**:&#9;&#9;&#9;Your Name
**Year**:&#9;&#9;&#9;1970
**Field 3**:&#9;&#9;&#9;This is information with</br>&#9;&#9;&#9;&#9;multiple lines, aligned using</br>&#9;&#9;&#9;&#9;tab characters

</info>

<!-- This indicates a manual page break -->
<pb></pb>

## Table of contents

* [Introduction: A clever title for your first chapter](#introduction) <pn>1</pn>
* [Topic A](#topic-a) <pn>2</pn>
* [Topic B](#topic-b) <pn>5</pn>
* [Topic C](#topic-c) <pn>7</pn>

<pb></pb>

## Introduction

This is regular text.

We just started a new paragraph by putting two line breaks. You can use **Markdown** _formatting_ everywhere or switch to HTML at any time, if you want to go beyond. Note, that justified text is enabled by default. This, along with any other setting related to typography and design, can be adjusted using CSS inside a single file: `doc.css`.

_Have fun writing!_

<pb></pb>

## Topic A

We just indicated a manual page break using the `<pb></pb>` tag. This will be taken into account by the web browser when printing this document, or saving it to PDF.

## Topic B

In order to print this document or to export it to pdf, simply convert it to HTML and print the resulting file using any modern web browser. For details, check out the `readme.md`.

Manual page breaks should be rendered in the printing preview.

<foot>² This is a footnote. You can add this element at the end of any page.</foot>

## Topic C

Since a footnote is considered the last element on a page, it indicates a manual page break just like the `<pb></pb>` tag.

```md

# Code

Markdown allows you to embed monospace code snippets like this.

For example, this is Markdown inside Markdown.

* Bullet Point

![Image](file)

```
