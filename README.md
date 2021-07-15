# About
This repository contains the files that I used for my master thesis on quintessence. It is for your convenience if you'd like to reproduce my results and it serves as a backup for myself and future reference. I'd like to thank the creators and maintainers of the following projects:

xAct: http://xact.es

xPand: http://www2.iap.fr/users/pitrou/xpand.htm

CLASS: https://lesgourg.github.io/class_public/class.html

MontePython: https://brinckmann.github.io/montepython_public/


# mathematica
Equations of Motion from a Lagrangian / an Action

This rep contains mathematica files that use the xAct packages xPert and xPand to derive the equations of motion from a specified Lagrangian in a flat Friedmann-Lemaître-Robertson-Walker (FLRW) universe with a first order perturbation in a scalar-vector-tensor (SVT) decomposition.

All definitions are self-contained in each notebook, i.e. the notebook should run stand-alone. However, xPand starts with the abstract expressions derived using xPert that are included in the xPert.nb.

A big thanks to the xAct user group https://groups.google.com/g/xact and its committed members.

## xPert
Starting from the Lagrangian of a scalar field and interacting dark matter, the abstract expressions for the stress-energy-momentum tensor and the equations of motion are derived in this notebook.

## xPand
This notebook starts with the abstract notation (derived using xPert) and re-expresses everything in a metric-dependent way in a flat FLRW universe with a S-V-T decomposition.

# CLASS
The obtained equations are implemented in the CLASS code (https://github.com/lesgourg/class_public). Uploaded here are the full source code files that were changed. Please note that only the changes marked with 'KBL' or 'HVR' are our own work. Credits for everything else go to the CLASS maintainers. Our fork is based on CLASS 2.9.4.
## \*.c-Files
The \*.c-files uploaded here are meant to replace the corresponding files in the folder 'source' of the official CLASS code base.
## \*.h-Files
The \*.h-files uploaded here are meant to replace the corresponding files in the folder 'include' of the official CLASS code base.
## \*.pyx\*-Files
The \*.pyx\*-files uploaded here are meant to replace the corresponding files in the folder 'python' of the official CLASS code base.


All other files remained untouched and are to be taken from the official CLASS repository.
