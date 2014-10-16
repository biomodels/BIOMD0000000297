# BIOMD0000000297: Ciliberto2003_Morphogenesis

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000297.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000297.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000297 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**Mathematical model of the morphogenesis checkpoint in budding yeast.**   
Ciliberto A, Novak B, Tyson JJ _J. Cell Biol._ [2003 Dec; Volume: 163 (Issue:
6 )] Page info: 1243-54
[14691135](http://www.ncbi.nlm.nih.gov/pubmed/14691135) ,  
**Abstract:**   
The morphogenesis checkpoint in budding yeast delays progression through the
cell cycle in response to stimuli that prevent bud formation. Central to the
checkpoint mechanism is Swe1 kinase: normally inactive, its activation halts
cell cycle progression in G2. We propose a molecular network for Swe1 control,
based on published observations of budding yeast and analogous control signals
in fission yeast. The proposed Swe1 network is merged with a model of cyclin-
dependent kinase regulation, converted into a set of differential equations
and studied by numerical simulation. The simulations accurately reproduce the
phenotypes of a dozen checkpoint mutants. Among other predictions, the model
attributes a new role to Hsl1, a kinase known to play a role in Swe1
degradation: Hsl1 must also be indirectly responsible for potent inhibition of
Swe1 activity. The model supports the idea that the morphogenesis checkpoint,
like other checkpoints, raises the cell size threshold for progression from
one phase of the cell cycle to the next.

The model reproduces Fig 3 of the paper.

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html) .  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


