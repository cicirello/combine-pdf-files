# combine-pdf-files

Use pdflatex to combine multiple pdf files with the following steps:
1. Make sure you have an up to date LaTeX system installed such as [TeX Live](https://www.tug.org/texlive/).
2. Read the comments in the file [CombinePDFs.tex](CombinePDFs.tex).
3. Edit the lines in that file where indicated with the names of the pdfs you want 
  to combine in the order you want them to appear in the result, including specifying 
  page ranges if you don't want the entire pdf files.
4. Run `pdflatex CombinePDFs.tex` at the command line, which will produce a file named `CombinePDFs.pdf`.
5. You can then rename the pdf file, or alternatively, you can name the `tex` file as
  desired before you begin.

## Blog Post Explaining Usage

> [Combine Multiple PDF Files Into One Using pdfLaTeX](https://dev.to/cicirello/combine-multiple-pdf-files-into-one-using-pdflatex-3ljb), posted on DEV on September 14, 2022.
