# MODEL1006230057: Moore2004_CML_TcellInteration

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1006230057.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1006230057.git@20140916`

## Usage

Importing the model package.

`import MODEL1006230057 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**A mathematical model for chronic myelogenous leukemia (CML) and T cell interaction.**   
Moore H, Li NK. _J Theor Biol_ 2004 Apr 21;227(4):513-23
[15038986](http://www.ncbi.nlm.nih.gov/pubmed/15038986) ,  
**Abstract:**   
In this paper, we propose and analyse a mathematical model for chronic
myelogenous leukemia (CML), a cancer of the blood. We model the interaction
between naive T cells, effector T cells, and CML cancer cells in the body,
using a system of ordinary differential equations which gives rates of change
of the three cell populations. One of the difficulties in modeling CML is the
scarcity of experimental data which can be used to estimate parameters values.
To compensate for the resulting uncertainties, we use Latin hypercube sampling
(LHS) on large ranges of possible parameter values in our analysis. A major
goal of this work is the determination of parameters which play a critical
role in remission or clearance of the cancer in the model. Our analysis
examines 12 parameters, and identifies two of these, the growth and death
rates of CML, as critical to the outcome of the system. Our results indicate
that the most promising research avenues for treatments of CML should be those
that affect these two significant parameters (CML growth and death rates),
while altering the other parameters should have little effect on the outcome.

This model was taken from the [CellML
repository](http://www.cellml.org/models) and automatically converted to SBML.  
The original model was: [ **Moore H, Li NK. (2004) - version=1.0**
](http://models.cellml.org/exposure/f1aaa04a7e0de5bf974d296a1ff9dd25)  
The original CellML model was created by:  
**Catherine Lloyd**   
c.lloyd@auckland.ac.nz  
The University of Auckland  

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not..  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


