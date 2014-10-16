# BIOMD0000000199: testid

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000199.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000199.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000199 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes
This is a model of neuronal Nitric Oxide Synthase expressed in Escherichia
coli based on [Santolini J. et al. J Biol Chem. (2001) 276(2):1233-43](http://
www.ncbi.nlm.nih.gov/entrez/query.fcgi?cmd=Retrieve&db=pubmed&dopt=Abstract&li
st_uids=11038356) .  
Differing from the article, oxygen explicitly included in the reaction 2, 5
and 10 (numbers as in scheme 1 in the article). In the article the assumed
oxygen concentration of 140 uM was included in the pseudo first order rate
constant.  
Fig 2E in the article shows different time courses for citrulline and NO than
the ones produced by this model. Dr. Santolini, one of the authors of the
article, wrote that the legends in fig. 2E might be mixed up and should rather
denote NO and NO3 instead of citrulline and NO.  

This model originates from BioModels Database: A Database of Annotated
Published Models. It is copyright (c) 2005-2009 The BioModels Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html) .  
To cite BioModels Database, please use [Le Novère N., Bornstein B., Broicher
A., Courtot M., Donizelli M., Dharuri H., Li L., Sauro H., Schilstra M.,
Shapiro B., Snoep J.L., Hucka M. (2006) BioModels Database: A Free,
Centralized Database of Curated, Published, Quantitative Kinetic Models of
Biochemical and Cellular Systems Nucleic Acids Res., 34: D689-D691.](http://ww
w.pubmedcentral.nih.gov/articlerender.fcgi?tool=pubmed&pubmedid=16381960)


