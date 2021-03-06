# __Thesis_chida template__
### Created by Oscar Barragán
### e-mail: oscaribv@gmail.com
### Updated: june 29, 2015


This thesis template can be used, modified and distributed freely.
I have compiled this template using texmaker and in the terminal using 
pdflatex and latex.

##Contents

* ./paquetes 
  this directory contains packages and commands files: packages.tex and commands.tex
    * packages.tex:
        * PACKAGES SECTION: contains all the packages, such as nomencl, hyperref, etc. 
  Some of them can not be installed in your computer. Be sure you have them 
  before compiling to avoid errors.
        * FCHAPTER SECTION: contains some definitions which create a nice header for each
  chapter. Check the definition of the package fncychap.
        * HYPERREF SECTION: Modifies the default hyperref package. __Put your name in pdfauthor!__
  linkcolor, citecolor, etc. generate the nice link color in the thesis, change
  the color if you want.
     * commnads.tex:
  Here there are some predefined commands, abstract and blackpage are used in the thesis,
  do not erase them.
  Below Defined commands for this thesis, you can define some commands that you can use
  in your document, I have put some examples, but you can define others.  

* ./frontmatter
 this directory contains the files you must use in the first pages of your thesis.
    * front.tex: 
  here you define the front page of your thesis. You can add your University
  logo, your name and more stuffs.
    * template.tex:
  here is the link to this thesis template, if you liked, share it.
 dedicatory.tex: 
  If you have somebody special put it here ;)
    * abstract.tex:
  Put your abstract between \begin{abstract} and \end{abstract}, I put the question
  you have to ask in order to write a perfect abstract.
    * acronyms.tex:
  If you use some acronyms in your thesis, it is a great idea to define them in a
  single page.

* ./mainmatter
 this directory contains the fun part of your thesis.
 Write an introductionn, conclusions, and some chapters describing your work.
    * introduction.tex:
  here you have to write your introduction, I wrote some examples of citings.
    * chap2.tex: 
  the second chapter of your chapter, you have to add more chapters if you need them.
  choose a nice title.
    * conclusions.tex
  If you worked hard, you must have some nice conclusions. Write them here.

* ./appendix
  this directory contains a sample of an appendix, it has the same form that for
  chapters.
     * ap1.tex: 
   Change the title and write a lot!

* ./bibliography
  this directory contains the data to generate automatic bibliography with BibTeX.
     * refs.bib:
   This file contains a lot of bibliography to generate automatically the bibliography
   in your document. Use Mendeley or related software to generate this kind of files
   automatically.
     * astroads.bst:
   this file contains your bibliography style. This template was written for an astronomer,
   then this style is used in some astronomy documents. You can search for another *.bst
   file in order to adapt it to your requirements.


