<!--
author: Elizabeth Drellich

-->


# Agenda

As part of the LIEAF 2022 Workshop on [Creating Open Source Informatics Instructional Resources](https://github.com/arcus/LIEAF2022_workshop/tree/joy-github), we will transform a plain text file first into a markdown file.

After learning the basics of markdown, we will add more features using LiaScript.

## Text to Markdown
In your forked copy of the PBJ repository:

1. Make a copy of the `PBJ_text.txt` file.
2. Change file extension from `.txt` to `.md`.
3. Rename the file if you want.
4. Toggle Markdown Preview to the file you are editing.

### Text Formatting
- headings
- **bold**
- _italics_

> block quotes

- _**bold-italics**_
- linking to [websites](https://github.com)

### Images
- Inserting an image
- path to the image
- using alt-text

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

|Example | Table | Here |
| - | -: | :- |
|1|2|3|
|look | at my | table |

### Code Blocks
- generic code block: put `\`\`\``  on its own line both before and after the code.
- specifying a language for code block highlighting: after the opening `\`\`\`` include the name of the language like `\`\`\`python` or `\`\`\`r`
- inline code `code here`

## Markdown to LiaScript
* Keep the file extension as `.md`
* Toggle LiaScript previewer to the file you are editing.

### Metadata and YAML
* open with `<!-- yaml: here -->`

### Video and Audio
* insert video
* explain `!?[]()` format for video and `?[]()` for audio files

### Displaying Data

Look at the buttons next to the two tables we already made:

* Bar charts/line graphs
* Pie chart

### Quizzes
* Multiple choice (one or multiple correct answers)
* Hints
* Answers **first look at incorporating html to push capabilities farther**

## Publishing your course
Make sure you commit your work to GitHub!!!

Then...

* Markdown renders on GitHub directly
* Go to liascript.github.io
* Enter the web address of your `.md` file.
* Obtain rendered course.

You can share this rendered course directly with learners.
