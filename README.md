# Individual Antibiotic Treatments

The general aim of this project is to design optimal individual (that is, personalized) antibiotic treatments based on microbiota composition to reduce resistance. Here we test the effects of time-dependent versus concentration-dependent antibiotics on bacterial communities with only two different bacteria species, called commensal and pathogen.

## Getting Started

### Prerequisites

The whole code was build in Julia version 0.5.1 and requires Gadfly, ODE, Distributions, DataFrames and JLD packages to be installed. 

### Files Description

There are two .ipynb files, "name" and "name2". The first one is como contenido en si mismo, while the second calls individual modules (i.e. .jl source files).

"name" file offers visualization of figures on the notebook itself, hence can be used when running few experiments. Whereas "name2" should be used when running many experiments at once, figures are stored at different folders according to running time.

#### Source files

Monod.jl

MoParams.jl

PKPD.jl

PlottingFunctions.jl

SystemODE.jl

TreatmentSimulator.jl



```
Some code
```
