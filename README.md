# RHEED-analysis-with-C++

A time-ecient, 
exible, and user friendly computer model has been developed to study the growth
of thin epitaxial lms with RHEED. The main functionality of the model is its ability to analyze the
growth of layers and perform dynamical calculations of amplitude of the RHEED specular beam intensity
oscillations as a function of growth time using the scattering potential for heteroepitaxial structures.

The open source simulation code written in C++ can be easily executed by any user whose knowledge
of high-level programming techniques is not the most important in research work. It must also give freedom
for the user to modify code to implement new models and analyze them. In achieving those goals, Rheedsim
gives the user a user friendly, easily modiable approach to anaylse growth models and RHEED data.
Rheedsim has 2 main objectives, simulating growth models and carrying out dynamical calculations
on a growing epitaxial surface. In simulating the growth, it allows the user to carry out simulations for
4 models, i.e. the diusive growth and 3 variations of the distributed growth. Either Dormand{Prince
fth-order Runge{Kutta method or the Cash-Karp Karp fourth and fth order Runge Kutta method with
error estimation and adaptive step-size control6 could be used for solving the initial value problem for the
non-linear dierential equations. It also uses input data from the inputGrowthData.dat text le where the
user can provide information on the parameters of the simulation of growth of thin epitaxial lms.
In terms of dynamical calculations, Rheedsim calculates the crystal potential of the substrate and the
epitaxial layer and then the grazing angle of the electron beam for the layers of the epitaxial layer growing
on top of the substrate.


