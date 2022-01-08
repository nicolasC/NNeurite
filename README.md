# NNeurite
Artificial neuronal networks for the unsupervised extraction of axonal and dendritic time-lapse signals

NNeurite is a set of mathematical and computational techniques specialized for the analysis of time-lapse microscopy images of neurite activity in small behaving animals. Starting from noisy and unstable microscopy images containing an unknown number of small neurites, NNeurite simultaneously aligns images, denoises signals and extracts the location and the temporal activity of the sources of Ca2+ transients.

At the core of NNeurite is a novel artificial neuronal network (NN) which we have specifically designed to solve the non-negative matrix factorization (NMF) problem modeling source separation in fluorescence microscopy images.

- We have embedded non-rigid image alignment in the NMF optimization procedure, hence allowing to stabilize images based on the transient and weak neurite signals. 
- NNeurite processing is free of any human intervention as NN training is unsupervised and the unknown number of Ca2+ sources is automatically obtained by the NN-based computation of a low-dimensional representation of time-lapse images.
- The spatial shapes of the sources of Ca2+ fluorescence are not constrained in order to automatically extract the micrometer-scale details of dendritic and axonal branches, such dendritic spines and synaptic boutons. 

# Requirements
Python 3
Tensorflow with GPU support.

# Main developper
Nicolas Chenouard
