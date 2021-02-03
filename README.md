# My MSc thesis

References are in BibLaTeX format.

For citations, the following packages are required (in addition to the core TinyTex build):
  * `biber`
  * `biblatex-apa`

## Compiling the LaTeX document

### Compilation with `tinytex` (Windows or Linux)

1. After installing R, install [`tinytex`](https://yihui.name/tinytex/).
2. Run `tinytex::install_tinytex()` to install the TinyTeX LaTeX distribution.
3. Install the packages `latex` and `language-latex` within the Atom text editor.
4. To tell the Atom text editor to use your TinyTex installation for compilation using the `latex` package, in Settings go to `Packages/LaTeX` and provide the full path to the TinyTex distribution under **TeX Path** (e.g. `C:\Users\Liam\AppData\Roaming\TinyTeX`).

### Compilation with MiKTeX (Windows)

1. Install the packages `latex` and `language-latex` within the Atom text editor.
2. Download and [Strawberry Perl for Windows](https://strawberryperl.com/) then restart your PC.
3. Download and install [MiKTeX for Windows](https://miktex.org/download).
4. To tell the Atom text editor to use your MiKTeX installation for compilation using the `latex` package, in Settings go to `Packages/LaTeX` and provide the full path to your MiKTeX distribution. This path can be found by starting the MiKTeX Console application, going to Settings -> Directories and looking under "Link target directory."

## Exporting my Zotero library for creating the .bib file

Using the [Zotero BetterBibTeX plugin](https://github.com/retorquere/zotero-better-bibtex), start Zotero and go to `File > Export Library...`, then choose Format: Better BibLaTeX, uncheck all boxes, then click 'OK'.

## Custom commands

For commonly used commands, new commands were created or existing commands were renewed.

### Dummy references

To insert a reminder that a reference is required at a specific point in the text, I created new *dummy reference* commands.
To insert a dummy literature reference: `\dummyref`.
To insert a dummy figure reference: `\dummyfig`.
To insert a dummy table reference: `\dummytab`.
