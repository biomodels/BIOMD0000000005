# BIOMD0000000005: BIOMD0000000005

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000005.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000005.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000005 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Tyson1991 - Cell Cycle 6 var

Mathematical model of the interactions of cdc2 and cyclin.

This model is described in the article:

[Modeling the cell division cycle: cdc2 and cyclin
interactions.](http://identifiers.org/pubmed/1831270)

Tyson JJ.

Proc. Natl. Acad. Sci. U.S.A. 1991; 88(16); 7328-32

Abstract:

The proteins cdc2 and cyclin form a heterodimer (maturation promoting factor)
that controls the major events of the cell cycle. A mathematical model for the
interactions of cdc2 and cyclin is constructed. Simulation and analysis of the
model show that the control system can operate in three modes: as a steady
state with high maturation promoting factor activity, as a spontaneous
oscillator, or as an excitable switch. We associate the steady state with
metaphase arrest in unfertilized eggs, the spontaneous oscillations with rapid
division cycles in early embryos, and the excitable switch with growth-
controlled division cycles typical of nonembryonic cells.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[BIOMD0000000005](http://identifiers.org/biomodels.db/BIOMD0000000005) .

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024) .

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.


