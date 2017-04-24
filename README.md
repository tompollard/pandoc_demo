# Pandoc demo

This project gives a simple example of conversion from Markdown to HTML, PDF, DOCX, etc using [Pandoc](http://pandoc.org/). We use Pandoc to convert this Markdown-formatted readme file (README.md) into the following formats:

- PDF 
- HTML
- LaTeX
- DOCX
- RTF

The files are created in a directory named `output`.

## What is Markdown?

Markdown is plain text that follows a set of loosely defined syntax rules (e.g. lines beginning with `#` are first level headings, lines beginning with `##` are second level headings, wrapping words in `**` indicates bold text, a series of `*` or `-`  can be used to create lists, etc). 

From [Wikipedia](https://en.wikipedia.org/wiki/Markdown):

> Markdown is a lightweight markup language with plain text formatting syntax. It is designed so that it can be converted to HTML and many other formats using a tool by the same name. Markdown is often used to format readme files, for writing messages in online discussion forums, and to create rich text using a plain text editor.
> 
> John Gruber created the Markdown language in 2004 in collaboration with Aaron Swartz on the syntax, with the goal of enabling people 'to write using an easy-to-read, easy-to-write plain text format, and optionally convert it to structurally valid XHTML (or HTML)'. 
> 
> The key design goal is readability – that the language be readable as-is, without looking like it has been marked up with tags or formatting instructions, unlike text formatted with a markup language, such as Rich Text Format (RTF) or HTML, which have obvious tags and formatting instructions. 

## Syntax  

For an outline of basic Markdown syntax, see: [https://en.wikipedia.org/wiki/Markdown#Example](https://en.wikipedia.org/wiki/Markdown#Example).  

## How to use this demo  

### Install Pandoc

1. Install Pandoc by following the instructions for your operating system at: [http://pandoc.org/installing.html](http://pandoc.org/installing.html)
2. Open a terminal shell by following the instructions at: [http://pandoc.org/getting-started.html](http://pandoc.org/getting-started.html).
3. Check that Pandoc is installed by running the following command from the terminal: `pandoc --version`. If Pandoc is installed correctly, you should see an output that includes the version number.

### Copy the Pandoc-demo project from Github

1. Find this repository on GitHub (https://github.com/tompollard/pandoc_demo). Clone the repository (copy the repository to your computer) by following the instructions at: [https://help.github.com/articles/cloning-a-repository/](https://help.github.com/articles/cloning-a-repository/)

### Run Pandoc

1. Open a terminal shell by following the instructions at: [http://pandoc.org/getting-started.html](http://pandoc.org/getting-started.html) and change to the `pandoc_demo` directory that contains this README file.
2. Run the following command to create a PDF version of the the README.md file in the `output` directory: `pandoc README.md -o output/README.pdf` 
3. Try creating other formats by replacing `.pdf` with `.html` (HTML), `.tex` (LaTex), `.docx` (Word compatible .docx) and `.rtf` (Rich Text Format). 






