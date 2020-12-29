# Deep-Learning-Model-to-learn-physics-of-2D-heat-conduction

This project aims to develop a Machine Learning Model that can predict the steady‐state temperature distribution for simple geometries, given boundary conditions. This method offers a significant advantage over conventional methods such as the finite element method, which is computationally costly.

Initially, we employed a regular Convolutional Neural Network as the model. This model was too slow in converging to the desired function. Hence we had to improvise and adopt a Residual Neural Network(ResNet) architecture, which dramatically reduces the training time.

## Data Set Source
**Edalatifar, Mohammad; Tavakoli, Mohammad Bagher; Ghalambaz, Mohammad; Setoudeh, Farbod (2020),
“A dataset for conduction heat transer and deep learning”, Mendeley Data, V1, doi: 10.17632/rw9yk3c559.1**

## Data Source
Each sample in this dataset contains a two-channel image as the input and a one-channel image as the output of 64×64 pixels.

## Results

![True-vs-Predicted](https://raw.githubusercontent.com/HarshitMeda/Deep-Learning-Model-to-learn-physics-of-2D-heat-conduction/main/true_vs_predicted.jpg)

As it can be seen from the above image, we were succesful in modeling 2D Heat Conduction.
