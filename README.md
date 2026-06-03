Chemical segregation is a critical mechanism to optimize mechanical properties by tailoring local interfacial structure. Here we developed a machine learning framework to dicover eutectic compositionally complex alloys (ECCAs) with high segregaition propensity. It consists of two models, a conditional variational autoencoder (CVAE) and an artificial neural network (ANN). While the CVAE model can directly generate ECCAs, the ANN model will assess their likelihood undergoing chemical segregation. 

# System Requirements
Running these files only requries a standard computer with enough RAM. In our study, we use the computer with following configurations:
    CPU: Intel Core i7-10750H
    RAM: 16GB
    GPU: NVIDIA GeForce 1650Ti
With this configuration, the program can be readily executed.

# Softwar Requirements
All codes are run on Windows operating systems.
## 1. CVAE model
The CVAE model is trained using Pthon 3.14 with following packages:
    torch, pandas, numpy, openpyxl, matplotlib.pyplot
## 2. ANN model
The ANN model is trained using Matlab R2021b with following toolboxes:
    Statistics and Machine Learning Toolbox, Deep Learning Toolbox
