This gist contains [`out.tex`](#file-out-tex), a tex file that adds a PDF outline ("bookmarks") to the freely available pdf file of the book

*The Elements of Statistical Learning* (2nd ed),
by Trevor Hastie, Robert Tibshirani, and Jerome Friedman

https://web.stanford.edu/~hastie/ElemStatLearn/

The bookmarks allow to navigate the contents of the book while reading it on a screen.

### Usage ###

* download https://web.stanford.edu/~hastie/ElemStatLearn/printings/ESLII_print12.pdf
  as `in.pdf`
* download [`out.tex`](#file-out-tex) into the same folder as `in.pdf`
* compile as `pdflatex out.tex`
* rename the resulting output file `out.pdf` to e.g.
  `Hastie, Tibshirani, Friedman - The Elements of Statistical Learning.pdf`
  