# Data Analysis of Liquid Jet Impingement Simulations & Experiments

Athena Liu

## Problem Description

Liquid jet impingement is relevant to many industrial applications such as coating, cooling and cleaning. Under certain operating conditions, when the liquid jet hit the moving wall, it will spread smoothly into a thin layer of film and deposits onto the surface. This phenomenon is called “deposition”. My research attempts to understand the underlying physics of the jet deposition phenomenon. The major objective of the research is to figure out how the operating parameters, such as the jet speed, the wall moving speed and the liquid properties, would affect the spreading characteristics of the jet. 

## Data Analysis

I use a combination of experimental methods and computational simulations to accomplish my research goal.

- `./2D-planar-jet` : For 2D planar jet impinging on a moving wall, I have conducted a range of simulations using ANSYS Fluent, and recorded the steady-state results in the data sheets. Then I compare the simulation results with the scaling theory that I derived from boundary layer analysis.
- `./3D-round-jet` : For 3D round jet impinging on a moving wall, I have obtained the experimental data from previous researches and compared the results with my scaling theory.

## Python Skills

Some of the packages that I used include:
- numpy 
- pandas
- scipy
- matplotlib
- plotnine