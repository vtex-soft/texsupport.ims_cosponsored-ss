# SS

## DESCRIPTION

LaTeX author support files for IMS co-sponsored journal: 
[Statistics Surveys (SS)](https://imstat.org/journals-and-publications/statistics-surveys/)

## FILE LIST

-   `ss-sample.tex` - sample article for SS (source file)
-   `ss-sample.pdf` - sample article for SS (PDF compiled)
-   `figure1.eps`, `figure1.pdf` - sample figures for `ss-sample.pdf`
-   `LICENSE` - a copy of the LaTeX Project Public License
-   `README.md` - this file itself!
-   `imsart.cls`, `imsart.sty` - LaTeX style files
-   `acmtrans-ims.bst`, `imsart-nameyear.bst`, `imsart-number.bst` - BibTeX style files

## INSTRUCTIONS FOR SS AUTHORS

-   You only need `imsart.cls`, `imsart.sty`, `ss-sample.tex`, and `ss-sample.pdf`
-   Take the time to read `ss-sample.pdf`
-   Copy `ss-sample.tex` into `yourname.tex`
-   Edit `yourname.tex` (update metadata and the content of the paper)
-   Use `acmtrans-ims.bst`, `imsart-nameyear.bst`, `imsart-number.bst` BibTeX styles to prepare bibliography file. 
    More information can be found [here](http://www.bibtex.org/Using/) 
    or [here](https://www.latex-tutorial.com/tutorials/bibtex/).
-   Be sure to have `imsart.cls`, `imsart.sty` in the same directory (or any dir scanned for `cls`)
-   Compile `yourname.tex` to generate `yourname.pdf` with a `pdflatex` or `lualatex` program and check the result
-   More detailed instructions for authors are available on Internet: https://imstat.org/journals-and-publications/statistics-surveys/

## TROUBLESHOOTING

-   To remove frame from the text box use document class option `noshowframe`, e.g:

        \documentclass[ss,noshowframe]{imsart}

## BUG REPORTS

Please submit bug reports and/or feature requests
at [GitHub page](https://github.com/vtex-soft/texsupport.ims_cosponsored-ss/issues) or 
[latex-support@vtex.lt](mailto:latex-support@vtex.lt).
