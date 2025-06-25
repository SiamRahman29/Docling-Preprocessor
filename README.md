# Docling-Preprocessor

Docling crashes on large files because it can sometimes timeout on tasks. Therefore, we need preprocessing measures to split the large files into smallers chunks and sometimes compress the files before splitting. 

In this repository, a preprocessing script is written to preprocess a PDF file for Docling. Alongside the required packages, this script also requires a Ghostscript installation from [this link](https://ghostscript.com/releases/gsdnld.html).