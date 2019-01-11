# Hayai-Annotation Plants

R-package for an Ultra-Fast and Comprehensive Gene Annotation in Plants

Description
-----------
Hayai-Annotation-Plants is an R-package with a shiny-browser interface for a highly accurate and fast gene annotation system for plant species (Embryophyta). 

Hayai-Annotation-Plants provides five levels of annotation: 

1) Gene Name; 
2) Gene Ontology (GO) consisting of three main domains (Biological Process, Molecular Function and Cellular Component); 
3) Enzyme Commission Code (EC); 
4) Protein Existence Level; 
5) Evidence Code for GO annotation.


Documentation
-------------
For downloading, installing and running **Hayai-Annotation Plants** please see [Hayai-Annotation-Plants wiki](https://github.com/kdri-genomics/Hayai-Annotation-Plants/wiki) 

Reference
---------
Hayai-Annotation Plants: an ultra-fast and comprehensive gene annotation system in plants <br/>
Andrea Ghelfi, Kenta Shirasawa, Hideki Hirakawa, Sachiko Isobe <br/>
doi:[https://doi.org/10.1101/473488](https://www.biorxiv.org/content/early/2018/11/20/473488) 

Updates
-------
2019/01/04. Low number of input sequences crash - Fixed. Now, graphics are generated if number of annotated input queries are higher than 500.<br/>
2019/01/04. Hayai-Annotation Plants run with even if USEARCH is installed in another directory (requires symbolic link).
