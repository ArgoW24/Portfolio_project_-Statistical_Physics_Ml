# PROJECT TITLE: Predicting Phase Transitions in Statistical Physics

## NON-TECHNICAL EXPLANATION OF YOUR PROJECT
This project uses machine learning to predict phase transitions in physical systems. Using Monte Carlo simulation data, the model identifies key properties that signal shifts in material states. It provides insights into understanding complex systems in physics.

## DATA
The dataset comprises 10,000 samples from Monte Carlo simulations of a 2D Ising model. Each sample contains configuration states, temperatures, and corresponding energies. Data is generated in the code].

## MODEL
A Convolutional Neural Network (CNN) was chosen due to its ability to capture spatial dependencies in the configurations.

## HYPERPARAMETER OPTIMISATION
Hyperparameters such as learning rate, dropout rate, and kernel size were optimised using Bayesian Optimisation.

## RESULTS
The model achieved an accuracy of 92% in classifying states near the critical temperature. Insights include identifying the features most indicative of phase transitions.