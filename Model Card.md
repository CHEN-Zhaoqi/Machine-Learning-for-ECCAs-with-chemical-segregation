# Model Card for CVAE
A CVAE enables the generation of ECCAs.
## Model Description and Uses for CVAE
This CVAE model is designed for the direct generation of ECCAs. It consists of an encoder that maps descriptors into a latent space, and a decoder that reconstructs descriptors from latent codes conditioned on specified structures(i.e. eutectic structures). By conditioning the generative process on desired structures, the model enables targeted exploration of the alloy beyond known compositions.
    Developed by: Python 3.14
# Model Card for ANN
An ANN for prediction of likelihood that a alloy exhibits chemical segregation.
## Model Description and Uses for ANN
This ANN model is a feedforward neural network designed for chemical segregation propensity prediction. Given input descriptors,  the model predicts likelihood for chemical segregation. 
    Developed by: Matlab 2021b