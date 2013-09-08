This is my template project for my MTH 210 class at [Grand Valley State University][gvsu]. It is written in LaTeX using [SCons][scons] as a builder. This repository is a fork of my original [scons-latex][scons-latex] template with additional math conventions and definitions used in this class. Updates happen as I find more conventions set forth in the class.

[gvsu]: http://gvsu.edu/
[scons-latex]: https://github.com/seanfisk/scons-latex

Since it is a personal template, it is quite opionated on certain tools, such as:

* Use of [SCons][scons] for building the LaTeX document.
* Use of [LuaTeX][luatex] instead of [pdfTeX][pdftex].
* Use of [Biber][biber] instead of [BiBTeX][bibtex].
* Use of [Emacs][emacs] and [AUCTeX][auctex] for editing the document.
* Use of [Skim][skim] with [SyncTeX][synctex] for document viewing.

[scons]: http://scons.org/
[luatex]: http://www.luatex.org/
[pdftex]: http://www.tug.org/applications/pdftex/
[biber]: http://biblatex-biber.sourceforge.net/
[bibtex]: http://www.ctan.org/pkg/bibtex
[emacs]: http://www.gnu.org/software/emacs/
[auctex]: http://www.gnu.org/software/auctex/
[skim]: http://skim-app.sourceforge.net/index.html
[synctex]: http://mactex-wiki.tug.org/wiki/index.php/SyncTeX

To see how I use this template to build my PDFs from [Emacs][emacs], please take a look at the [TeX section of my Emacs configuration][sean-tex-emacs].

[sean-tex-emacs]: https://github.com/seanfisk/emacs/blob/sean/personal/personal-tex.el

**Note:** This template supports multi-file documents. If you change the name of the main document (i.e., `document.tex`), be sure to change the `TeX-master` directory variable in `.dir-locals.el`.
