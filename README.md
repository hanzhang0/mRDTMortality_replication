# Malaria Testing and Antibiotics Replication Repo

## Introduction
This repo contains the replication code for the paper "Widescale Diffusion of Malaria Testing Increased Antibiotic Use in Africa" by Han Zhang, Günther Fink, and Jessica Cohen (2022). 

## Code Structure 
All code is written in Stata 17. Replication code for all figures and tables that are generated with code is provided. It is assumed that the reader already has access to the publicly available household survey datasets and malaria testing data (as shown in the synthetic data provided, see section on "data structure" for more information). The dofiles are organized into five parts as follows: 

### descriptive.do
Code for all descriptive figures and tables, including the heatplot for mRDT distribution across study countries, sample composition for the full sample and tested subsample, and information on household characteristics and care seeking behaviors for the full sample and tested subsample. Replication code for the following tables and figures is included in this dofile:
- Figure 1
- Extended Data Table 1
- Extended Data Table 2
- Extended Data Table 3
- Extended Data Table 4

### regression_main.do
Code for all figures and tables that are generated from main regression models, including the overall impact estimates of mRDT distribution on blood testing and antibiotic use, residual plots, and forest plots for the heterogeneity analysis. Replication code for the following tables and figures is included in this dofile:
- Table 1
- Figure 2
- Figure 3

### regression_sensitivity.do
Code for all tables that are generated from sensitivity analysis, including the impact estimates for artemisinin-based drugs, leave-one-out analysis,  alternative non-linear model specifications, unweighted regression estimates, and per-under-five-child-fever-case alternative exposure. Replication code for the following tables and figures is included in this dofile:
- Extended Data Figure 1
- Extended Data Table 5
- Extended Data Table 6
- Extended Data Table 7
- Extended Data Table 8
- Extended Data Table 9
- Extended Data Table 10
- Extended Data Table 11
