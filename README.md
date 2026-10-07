# Modern Algebra II (2023 Fall) Lecture Note

This repository contains a LaTeX source file of the lecture note of Modern Algebra II (MAS312) course in 2023 Fall in KAIST. Instructor is Sanghoon Baek.

## Compilation

To compile this file, you need to use the following procedure. Using engines other than PDFLaTeX will produce PDF file with wrong font.
```
pdflatex "MAS312 Lecture Notes.tex"
makeindex "MAS 312 Lecture Notes.tex"
pdflatex "MAS312 Lecture Notes.tex"
pdflatex "MAS312 Lecture Notes.tex"
```

## Template Usage

Definitions should be written in `definition` environment. Theorems should be written in `theorem` environment. Lemmas should be written in `lemma` environment. Corollaries should be written in `corollary` environment.

Examples should be written in `example` or `examples` environment. To illustrate multiple examples consequently, use `examples` environment; do not use multiple `example` environments in a row. Also, `example` environment must contain a single example.

Proofs should be written in `proof` environment. The end-of-proof mark (■) is automatically attatched at the end of the box. If you need to specify the position of the end-of-proof mark (e.g. when the proof ends with list or displayed math environments), you can use `\qedhere` control sequence.
