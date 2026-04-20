# Surface Tension Prediction of Liquid Alloys

A machine-learning framework for predicting the surface tension of liquid alloys from alloy composition and temperature, with physically informed descriptors generated from elemental properties.

This repository provides a reproducible workflow for:

1. reading alloy composition and temperature data,
2. generating composition-based descriptors using `matminer`,
3. aligning features with the trained model input space,
4. predicting surface tension using a trained Extra Trees model, and
5. exporting the prediction results to an output file.

Input Format
The input file should contain:
one column for temperature: T (unit: K)
composition columns for alloy elements
compositions should be given as atomic fractions

Installation
You can install the required environment using either Conda or pip.

Citation
If you use this repository in your research, please cite the associated manuscript.
Title:
General Machine Learning Model with Thermodynamic-Consistency for Surface Tension Prediction of Liquid Alloys

Contact
For questions, bug reports, or collaboration, please contact:
Xindi Wang
[wang4339@126.com]
