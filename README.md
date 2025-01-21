# Identifying Critical Protein-Protein Interactions with Machine Learning
_This educational module will teach you how to apply machine learning methods to distiguish SARS-CoV-2 from SARS-CoV at the atomistic level. 

## Introduction
In this module, you wil learn how to apply machine learning (ML) methods to identify critical protein-protein interactions. This will allow you to distinguish the critical residues in making SARS-CoV-2 so much more infectious and lethal compared to SARS-CoV. 

The set of data that we have provided is molecular dynamics trajectories. Molecular dynamics (MD) is a type of biophysical simulation that looks how every atom in a particular biological system interacts with each other over a certain timescale. The output is known as a trajectory. It can be thought of as the "computational microscope into the cell." However, MD trajectories are a significant amount of data and can be difficult to analyze and parse through visually. 

This is where machine learning comes into play. We can take our MD trajectories and use that as an input for machine learning methods to analyze for us. In this particular situation, we have run MD on two distinct systems and would like to know the differences between them. More specifically, the two systems are SARS-CoV bound to the human receptor, hACE2, versus SARS-CoV-2 bound to hACE2. We would like to know exactly which residues on SARS-CoV-2 ended up driving the increased infectivity that led to the global pandemic we experiences in 2020. 

In this tutorial, we will apply three different ML approaches - random forest, logistic regression, and multi-layer perceptron. We will analyze the residues at the interface of where SARS-CoV or SARS-CoV2 bind to hACE2. More specifically, the input data is the inverse of the distance between the residues. The tutorial is split into three separate modules. 

## Tutorial modules
_All modules are accessed through Google Cloud Platform.

Module 1 - Introduction to PyMOL (molecular visualization software)
Note: If you don't have access to a PyMOL license, there is an online PyMOL GUI available in this tutorial here. Please locate relevant files in the folder titles "PyMOL-GUI" 

Module 2 - Introduction to Machine Learning Methods
Dependencies: 
sklearn
matplotlib.pyplot
numpy
pandas

Module 3 - Applying the ML Methods to Identify Critical Protein-Protein Interactions
Dependencies:
numpy
pandas
matplotlib
sklearn
os
sys
time

## Learning objectives

1 - learn the basics of biomolecule visualization with PyMOL
2 - understand the machine learning methods Random Forest, Multilayer Perceptron, and Neural Network
3 - apply the ML methods to determine which residues of SARS-CoV-2 lead to its increased infectivity compared to SARS-CoV

## Outcomes

Users of the module will 
1 - become comfortable and competent with the visualization software PyMOL and can apply the same skills in the visual analysis of their own biomolecules of choice
2 - understand the fundamentals of the three ML methods in the module and associated Python code to run them
3 - identify the key interactions that drive the increased binding strength of SARS-CoV-2’s RBD compared to SARS-CoV’s RBD to ACE2
4 - analyze complex and large datasets such as the MD trajectories provided 


