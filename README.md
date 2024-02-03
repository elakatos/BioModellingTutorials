# BioModellingTutorials

 Repository of mathematical models capturing various aspects of biological systems, to provide interactive tutorials for getting familiar with these systems and running simulations. All written in Python (version 3) in interactive Jupyter notebooks.
 For an introduction to mathematical models in biology (and other disciplines), check out the presentation **BioMath_introduction.pptx**.
 
## Population_growth
A model of simple (exponential) population growth. Here it is demonstrated on the population of Europe but can be used to model cellular growth in bacterial/cancer population.

## CancerTcell_model
A model of interaction between cancer and immune cells (killer T-cells). The model incorporates two types of T-cells to represent that not all T-cells will be effective against cancer cells. It simulates growth and death of each type of cell and different levels of interactions between (reactive) T-cells and cancer cells.

 ## Random_walk_1D
Jupyter notebook in Python that simulates a one-dimensional random walk (hopping left and right on a line), and introduction to stochastic modelling that incorporates randomness/uncertainty.  With some background reading references and bits of code left blank for practice.

## Stochastic_CancerTcell_model
A stochastic formulation of the first model from CancerTcell_model. Demonstrates how stochastic models are defined and how a single simulation step and a whole trajectory simulation is carried out, using Gillespie's Stochastic Simulation Algorithm (also known as the next reaction method).

## Stochastic_CancerTcell_model_updated
A continuation of the previous stochastic model, this notebook implements the updated (second) model from CancerTcell_model in a stochastic formulation. It also explores the final distribution of a measured population (in this case cancer cell population) and how to run multiple simulations to draw this distribution. Some blank lines to practice stochastic simulation.
