Christopher C. Strelioff
2012, Feb 19th

Overview:

This repository contains a set of lectures I developed to introduce R to 
undergraduate and graduate students for the class Mathematical and Computational 
Modeling in Ecology (UCLA, Winter 2012).  I assume the students have little or 
no programming experience and start with the very basics.  Ideally, these 
lectures should be coupled with lab examples and homework to practice the 
material.

I stopped during lecture to demostrate basic operations using the command line 
as well as rstudio.  Given this presentation style, the approximate lecture 
time was:

Lecture 01: 1 hour 15 mins
Lecture 02: 45 minutes
Lecture 03: 1 hour
Lecture 04: 1 hour

How to use:

The provided files are *.Rnw and makefiles for each lecture.  I use a complete 
install of Tex Live 2011 (including beamer and pgf/tikz) as well as a current 
version of R.  The lectures use Sweave to generate a *.tex file as well as a 
functional *.R script.

* If you are using Max/Linux, you should be able to type: 

  $make

* If you don't have make available, the commands executed to generate the 
slides are (assuming Lecture01 is being built):

  $R CMD Sweave Lecture01.Rnw 
  $pdflatex Lecture01.tex
  
The *.R script is generated using:

  $R CMD Stangle Lecture01.Rnw 

* Help

I provide these materials as examples for others to use and would welcome 
comments and suggestions, particularly if you find any errors.  Also, please let 
me know if you use this material.  I will attempt to answer questions when 
possible, but I can not promise a quick response in all cases.  Enjoy!