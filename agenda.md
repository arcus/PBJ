<!--
author: Elizabeth Drellich
email: drelliche@chop.edu
title: Workshop Agenda
version: 1.0
-->


# Agenda

As part of the LIEAF 2022 Workshop on [Creating Open Source Informatics Instructional Resources](https://github.com/arcus/LIEAF2022_workshop/tree/joy-github), we will transform a plain text file first into a markdown file.

After learning the basics of markdown, we will add more features using LiaScript.

## Text to Markdown
In your forked copy of the PBJ repository:

1. Make a copy of the `PBJ_text.txt` file.
2. Change file extension from `.txt` to `.md`.
3. Rename the file if you want.
4. Toggle the preview to the file you are editing using the "Open Preview" button in the upper right of the development screen.

![The "Open Preview" button is the leftmost icon in the upper right of the development screen.](media/screenshots/toggle_preview.png)

### Text Formatting
- headings
- **bold**
- _italics_

> block quotes

- _**bold-italics**_
- linking to [websites](https://github.com)

### Images
Images are similar to linking to websites, but require a `!` in front of the square brackets.

- path to the image goes in the parentheses
- alt text for the image goes in the square brackets

```
![Descriptive alt text.](path/to/image/file)
```

The alt text describes the information and function of the image.
A screen reader will announce "IMAGE" followed by your alt text.
Learn more about about [alt text](https://www.w3.org/WAI/tutorials/images/) from the World Wide Web Consortium.

### Lists
- itemized lists
* can use `-` or `*` to denote items

  - indenting matters
  - extra line before indented section

1. enumerated lists
3. the number `3.` doesn't matter for markdown
4. but does for LiaScript

### Tables
- `|` notation
- alignment using `:-:` notation

This code

```
|Example | Table | Here |
|    -   |    -: |   :- |
|1       |  2    |    3 |
|a|b|c|
```

is rendered by markdown as this table:

|Example | Table | Here |
|    -   |    -: |   :- |
|1       |  2    |    3 |
|a|b|c|

### Code Blocks
- generic code block: put `\`\`\``  on its own line both before and after the code.
- specifying a language for code block highlighting: after the opening `\`\`\`` include the name of the language like `\`\`\`python` or `\`\`\`r`
- inline code `code here`

## Markdown to LiaScript
* Keep the file extension as `.md`
* Toggle LiaScript previewer to the file you are editing.

### Including Media
* captions go in quotes: `![alt text description](file/path.jpg "caption in quotes")`

  * Captions will be displayed
  * A caption tells information related to the image, supplemental to the image itself.

    * Attribution
    * Interpretation
    * Commentary


* images can be arrayed in a gallery
* Other types of media can also be included:

  - `!?[]()`  for video
  - `?[]()` for audio files
  - `??[]()` for files of unknown type or interactive links.

### Displaying Data

Look at the buttons next to the two tables we already made:

* Bar charts/line graphs
* Pie chart

### Quizzes
* Multiple choice (one or multiple correct answers)
* Hints
* Answers **first look at incorporating html to push capabilities farther**


### Metadata and YAML
* Start document with a header: `<!--  metadata goes here   -->`

* Include metadata:
```
<!--
author: Elizabeth Drellich
email: drelliche@chop.edu
title: Workshop Agenda
version: 1.0
-->
```

* LiaScript specific tags:

  * `langague: en`
  * `narrator: UK English Female`

* Scripts and macros can also go in this header

## Publishing your course
Make sure you commit your work to GitHub!!!

Then...

* Markdown renders on GitHub directly https://github.com/arcus/PBJ/blob/main/PBJ_liascript.md


* Go to liascript.github.io
??[](https://liascript.github.io)

* Enter the url of your `.md` file.
* Obtain rendered course.

You can share this rendered course directly with learners.
