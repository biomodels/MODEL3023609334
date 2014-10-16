# MODEL3023609334: Ec_iAF1260_flux1

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL3023609334.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL3023609334.git@20140916`

## Usage

Importing the model package.

`import MODEL3023609334 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes

    
    
    organism        E. coli K-12 MG1655
    model   iAF1260
    Biomass Objective Function (BOF)        Ec_biomass_iAF1260_core_59p81M (E. coli biomass objective function (iAF1260) - core - with 59.81 GAM estimate)
    flux balance analysis objective maximize BOF
    Growth Associated Maintenance (GAM)     59.81 mmol ATP gDW-1
    Non-Growth Associated Maintenance (NGAM)        8.39 mmol ATP gDW-1 hr-1
    media conditions        computational minimal media
    carbon source   8 mmol glucose gDw-1 hr-1
    aerobic or anaerobic    18.5 mmol O2 gDw-1 hr-1
    additional constraints
    reactions constrained to zero   CAT, SPODM, SPODMpp, FHL
    flux split between reaction pairs       none

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


