# README.md

## Contents
* aastex.cls: The AASTeX class file
* ms.tex: Paper manuscript.
* natbib.sty: The natbib citation package (v7.1)
PRINTING THE GUIDE AND SAMPLES

The user guide is written in AASTeX preprint2 style.  
To print it out on a PostScript printer , you will need a DVI driver 
that will output to PostScript. If you wish to print to PostScript, 
and you are on a Unix or Linux system,  
the DVI driver on your computer system is probably called "dvips". 
To print out the user guide DVI file, type 

    prompt> dvips aasguide

To create and print your own DVI file, type

    prompt> latex aasguide
    prompt> latex aasguide
    prompt> dvips aasguide

There are various system- and program-specific eccentricities which
cannot be fully enumerated here.  Some things to watch out for:

    1.  On some systems, LaTeX does not permit a filename extension
	(the .tex) on the input file specification; .tex is assumed.

    2.  The user interfaces for DVI drivers are quite inconsistent.
	Some operate in an interactive mode, asking the user about
	variable setup parameters, while some only accept control
	input on the command line.

    3.  On some systems, DVI translation and printing are combined,
	so one would enter only one OS command after running LaTeX.
	This is typically the case for dvips.

Since LaTeX installations vary widely, you may need to consult 
the documentation for your particular installation or your local 
system administator for guidance in installing and using 
AASTeX.
 
ADMINISTRATIVE DETAILS

AASTeX was designed and written by Chris Biemesderfer in 1988.
Substantial revisions were made by Lee Brotzman and Pierre
Landau when the package was updated to v4.0.
AASTeX was rewritten as a LaTeX class by Arthur Ogawa for the
v5.0 release. It was updated to v5.2 by SR Nova Private Ltd.
The documentation has benefited from revisions by
Jeannette Barnes, Sara Zimmerman, and Greg Schwarz.

Comments, suggestions, complaints, and pleas for help can be sent
electronically to aastex-help@aas.org.

AASTeX Web site: http://aastex.aas.org/

CB, 20 May 1999
Rev. SZ, 2 Nov 2000
Rev. SZ, 14 Dec 2004
