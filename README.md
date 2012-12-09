# Scribble Protocol Language Specification

The repository contains the source latex files for the Scribble Protocol Language Specification.


## Building the PDF

You will first need to check that your system includes the _pdflatex_ utility. If you need to install this utility, then refer to the [TexLive](http://www.tug.org/texlive/) website.

To build the PDF representation of the spec, run the following command from the top level folder:

*mvn latex:latex*

Once the build is complete, the specification can be found in the _target_ folder.


