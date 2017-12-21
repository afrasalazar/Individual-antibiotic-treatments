# Individual Antibiotic Treatments

The general aim of this project is to design optimal individual (that is, personalized) antibiotic treatments based on microbiota composition to reduce resistance. Here we test the effects of time-dependent versus concentration-dependent antibiotics on bacterial communities composed of two different bacteria species, called commensal and pathogen.

## Getting Started

### Prerequisites

The code was entirely build in Julia version 0.5.1 and requires Gadfly, ODE, Distributions, DataFrames and JLD packages to be installed. 

### Files Description

There are two Jupyter notebook (.ipynb) files, "name" and "name2". The first one includes all the needed functions itself, while the second calls individual modules (i.e. .jl source files).

"name" file offers visualization of figures on the notebook, hence can be used when running few experiments. Whereas "name2" should be used when running many experiments at once, figures are stored at different folders according to running time.

#### Source files

Monod.jl Contains bacteria uptake funcion as a Monod function. 

MoParams.jl Contains all the parameters of the model and creates a dictionary of all of them.

PKPD.jl Includes the killing and the growth inhibition functions ($E_max models$)

PlottingFunctions.jl

SystemODE.jl

TreatmentSimulator.jl



```
Some code
```
