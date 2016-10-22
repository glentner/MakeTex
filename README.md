MakeTex
-------

Compile a LaTeX source file into a PDF document.


```
usage: maketex input_file [-bdmv] [-o | --output filename]
Compile a latex source file into a PDF document.

MakeTex wraps pdflatex and executes the compile statement on your
behalf, stashing build files under /tmp/.

options:
-v, --verbose        show compiler output
-d, --debug          show debugging information
-b, --bibliography   compile with bibtex after
-m, --monitor        file system watch, auto-compile
-o, --output         specify an alternate output PDF
-h, --help           show this message
```
