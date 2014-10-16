# BIOMD0000000434: MODEL1206010000

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000434.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000434.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000434 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


McAuley2012 - Whole-body Cholesterol Metabolism

Lipid metabolism has a key role to play in human longevity and healthy aging.
A whole-body mathematical model of cholesterol metabolism that explores the
changes in both the rate of intestinal cholesterol absorption and the hepatic
rate of clearance of LDL-C from the plasma, has been presented here. The model
showed that of these two mechanisms, changes to the rate of LDL-C removal from
the plasma with age had the most significant effect on cholesterol metabolism.

The original SBML model file was generated using MathSBML 2.5.1.

This model is described in the article:

[A whole-body mathematical model of cholesterol metabolism and its age-
associated dysregulation.](http://identifiers.org/pubmed/23046614)

Mc Auley MM, Wilkinson DJ, Jones JJ, Kirkwood TT.

BMC Syst Biol. 2012 Oct 10;6(1):130.

Abstract:

BACKGROUND: Global demographic changes have stimulated marked interest in the
process of ageing. There has been, and will continue to be, an unrelenting
rise in the number of the oldest old ( >85 years of age). Together with an
ageing population there comes an increase in the prevalence of age related
disease. Of the diseases of ageing, cardiovascular disease (CVD) has by far
the highest prevalence. It is regarded that a finely tuned lipid profile may
help to prevent CVD as there is a long established relationship between
alterations to lipid metabolism and CVD risk. In fact elevated plasma
cholesterol, particularly Low Density Lipoprotein Cholesterol (LDL-C) has
consistently stood out as a risk factor for having a cardiovascular event.
Moreover it is widely acknowledged that LDL-C may rise with age in both sexes
in a wide variety of groups. The aim of this work was to use a whole-body
mathematical model to investigate why LDL-C rises with age, and to test the
hypothesis that mechanistic changes to cholesterol absorption and LDL-C
removal from the plasma are responsible for the rise. The whole-body
mechanistic nature of the model differs from previous models of cholesterol
metabolism which have either focused on intracellular cholesterol homeostasis
or have concentrated on an isolated area of lipoprotein dynamics. The model
integrates both current and previously published data relating to molecular
biology, physiology, ageing and nutrition in an integrated fashion.

RESULTS: The model was used to test the hypothesis that alterations to the
rate of cholesterol absorption and changes to the rate of removal of LDL-C
from the plasma are integral to understanding why LDL-C rises with age. The
model demonstrates that increasing the rate of intestinal cholesterol
absorption from 50% to 80% by age 65 years can result in an increase of LDL-C
by as much as 34mg/dL in a hypothetical male subject. The model also shows
that decreasing the rate of hepatic clearance of LDL-C gradually to 50% by age
65 years can result in an increase of LDL-C by as much as 116mg/dL.

CONCLUSIONS: Our model clearly demonstrates that of the two putative
mechanisms that have been implicated in the dysregulation of cholesterol
metabolism with age, alterations to the removal rate of plasma LDL-C has the
most significant impact on cholesterol metabolism and small changes to the
number of hepatic LDL receptors can result in a significant rise in LDL-C.
This first whole-body systems based model of cholesterol balance could
potentially be used as a tool to further improve our understanding of whole-
body cholesterol metabolism and its dysregulation with age. Furthermore, given
further fine tuning the model may help to investigate potential dietary and
lifestyle regimes that have the potential to mitigate the effects aging has on
cholesterol metabolism.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels)
and identified by:
[MODEL1206010000](http://identifiers.org/biomodels.db/MODEL1206010000) .

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024) .

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.


