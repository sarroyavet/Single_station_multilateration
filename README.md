# LaserTRACER and Coordinate Measuring Machine comparison - script for distances between each target computation from measurement datas



This project was developed at Aix Marseille University, CNRS, ISM, Marseille, France.

This repository contains the implementation of a multilateration (LaserTRACER) and a sphere reconstruction (Coordinate Measuring Machine) algorithms based on Least-Square Method, and the results comparison (LT - CMM Comparison) from object measurement done at the laboratory. It is meant to be used with [MATLAB (R2024b)](https://fr.mathworks.com/products/matlab.html).

This Matlab module was created by Noah BERTIN. It allows understanding results differences between object measurement obtained via LaserTRACER and Coordinate Measuring Machine.



## Requisites

&#x20;   Matlab (Version R2024b recommended)



## General instructions

The "LaserTRACER" folder contains:

* Trac-CAL v2.1 Data: LaserTRACER measurement data obtained via Trac-CAL v2.1.
* MATLAB Scripts: Scripts used to perform multilateration to compute the distances between each target, and to estimate their uncertainties using the Monte Carlo method.
* MATLAB Results: .csv files containing the final results, which are used for subsequent comparisons.



The Coordinate Measuring Machine (CMM) folder contains:

* M-COSMOS Data: CMM measurement data obtained via M-COSMOS v5.
* MATLAB Scripts: Scripts used for sphere reconstruction to determine target centers, and to estimate their uncertainties using Jacobian propagation.
* MATLAB Results: .csv files containing the final results, which are used for subsequent comparisons.



## Research

The scripts of this repository were first used in ADD THE ARTICLE

