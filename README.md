# My MSc thesis

References are in BibLaTex format.
LaTeX distribution used was TinyTex (installed via R).
Text was written and compiled within Atom text editor using the package `latex`, and with `language-latex` for syntax highlighting.

For citations, the following packages are required (in addition to the core TinyTex build):
  * `biber`
  * `biblatex-apa`

## Compiling the LaTeX document

To tell the Atom text editor to use your TinyTex installation for compilation using the `latex` package, in Settings go to `Packages/LaTeX` and provide the full path to the TinyTex distribution under **TeX Path** (e.g. `C:\Users\Liam\AppData\Roaming\TinyTeX`).

## Exporting my Zotero library for creating the .bib file

Using the [Zotero BetterBibTeX plugin](https://github.com/retorquere/zotero-better-bibtex), start Zotero and go to `File > Export Library...`, then choose Format: Better BibLaTeX, uncheck all boxes, then click 'OK'.

## Custom commands

For commonly used commands, new commands were created or existing commands were renewed.

### Dummy references

To insert a reminder that a reference is required at a specific point in the text, I created new *dummy reference* commands.
To insert a dummy literature reference: `\dummyref`.
To insert a dummy figure reference: `\dummyfig`.
To insert a dummy table reference: `\dummytable`.
