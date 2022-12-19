# simple-report-template

This is a very simple template to jumpstart your short lab report writing.

It includes a variety of packages that you usually need in order to write.
The very narrow borders make you eco-friendly when you print the report out.

You can easily use two columns if you are one of those people.

The included fonts are [Atkinson Hyperlegible](https://brailleinstitute.org/freefont) for the main text and [Fira Code](https://github.com/tonsky/FiraCode) for code blocks. 
They are both great fonts, with the additional benefit of being free, open source and highly legible.

Your figures should live in `/resources/images`.
The bibliography file is `resources/bibliography.bib`, using `biber` as the back-end.
The glossary is `resources/glossary.tex`.

The main text should be included in the `./document.tex`, with the `main.tex` file reserved mainly for configuration.
You can write appendices in `appendices.tex`, and modify `main.tex` to include them.

Edit `main.tex` just with your information and the report title, then you're free to go.
