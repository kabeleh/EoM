# About
This repository contains the files that I used for my master thesis on quintessence. It is for your convenience if you'd like to reproduce my results and it serves as a backup for myself and future reference. I'd like to thank the creators and maintainers of the following projects:

xAct: http://xact.es

xPand: http://www2.iap.fr/users/pitrou/xpand.htm

CLASS: https://lesgourg.github.io/class_public/class.html

MontePython: https://brinckmann.github.io/montepython_public/


# Equations of Motion
Equations of Motion from a Lagrangian

This rep contains mathematica files that use the xAct package and different approaches to derive the equations of motion from a specified Lagrangian in a flat Friedmann-Lemaître-Robertson-Walker universe with a first order perturbation in a scalar-vector-tensor decomposition.

All definitions are self-contained in each notebook, i.e. the notebook should run stand-alone. However, xPand starts with the abstract expressions derived using xPert that are included in the EoM_xCoba.nb.

A big thanks to the xAct user group https://groups.google.com/g/xact and its committed members.

## xTras
The EoM_xTras.nb directly derives the equations of motion in a metric-dependent way.

## xCoba
The EoM_xCoba.nb derives abstract equation of motion using xPert and re-expresses these expressions then by the means of xCoba in a metric-dependent way.

## xPand
The EoM_xPand.nb starts with the equations of motion in abstract notation (derived using xPert) and re-expressed them in a metric-dependent way.

# CLASS
The obtained equations are implemented in the CLASS code (https://github.com/lesgourg/class_public). Uploaded here are the full source code files. Please note that only the changes marked with 'KBL' or 'HVR' are our own work. Credits for everything else go to the CLASS maintainers.
