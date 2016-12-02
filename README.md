# NeutralFlowOverHills
Neutral turbulent flow over axi-symmetric hills of varying steepness and roughness.

This repository contains data from a wind tunnel experiment in which turbulent flow was measured in vertical cross sections along the flow, over axi-symmetric ridges of varying steepness and roughness in the CSIRO boundary layer wind tunnel in the Pye Laboratory at Black Mountain Laboratories in Canberra.  The data is supplied in MS Excel files and is reasonably self explanatory, particularly with the aid of the BLM paper noted below.

The motivation for creating this repository came as we at Windlab were implementing OpenFOAM to do wind energy work.  In going from flow-in-a-box sorts of calculations to neutrally stratified turbulent flow over real topography with varying surface roughness and vegetative canopy types, we discovered there is very little data available for validation of tools such as OpenFOAM, inside or outside the scientific community.  Along the pathway from doing very simple calculations with OpenFOAM to ones that are a reasonable representation of turbulent flow in an atmospheric boundary layer, we benefitted from an understanding of a number of aspects about turbulent flow over hills that were arrived at by examination of the data made available here.  It is our hope that others will benefit from wading through this data and learning these and other things.  Some of the things we learned have been presented in a few published papers.  The experiment and some results are described in:

Ayotte, K.W. and Huges, D.E., 2004, Observations of Boundary-Layer Wind-Tunnel Flow Over Isolated Ridges of Varying Steepness and Roughness., Boundary-Layer Meteorology, 112, 525-556.

The data set contains LDA measurements of mean and turbulent moments from seven experiments, four over sand covered surfaces/hills ( smooth ) and three over peg covered surfaces/hills ( rough ). The flow parameters are given in the above noted paper. In both the smooth and rough experiments, the steepness varies between 0.2 (maximum slope ) and 0.6 and 0.4 for the smooth and rough surfaces respectively. Both the 0.6 smooth case and 0.4 rough case are fully separated.

The following references may be helpful in provide some context and a view of turbulent flow over hills.

Ayotte, K.W., 2008, Computational modelling for wind energy assessment, Journal of Wind Engineering and Industrial Aerodynamics, 96, 1571-1590.

ftp://ftp.atdd.noaa.gov/pub/cwe2010/Files/Papers/093_Ayotte.pdf

We hope you find the data useful.

Keith Ayotte
Chief Scientist
Windlab Limited
Canberra, Australia

