# MLP_Activation_Functions
Using a Custom “Peanut vs Donut” Dataset
Overview

This repository contains a complete tutorial exploring how activation functions influence the behaviour of Multilayer Perceptrons (MLPs).
The tutorial is supported by:

A custom nonlinear dataset (“Peanut vs Donut”)

A fully reproducible Jupyter notebook

Automatically exported visual figures

A written PDF report/tutorial explaining the concepts in depth

The project is designed for students, instructors, and practitioners who want to understand why activation functions matter, how they impact optimisation, and how they shape decision boundaries in neural networks.

What This Tutorial Covers

What MLPs are and why activation functions are essential

Comparison of four activations: Sigmoid, Tanh, ReLU, Leaky ReLU

How activations affect:

Gradient flow

Learning speed

Generalisation

Decision boundary complexity

Hands-on demonstration using a unique synthetic dataset

Exported figures for easy inclusion in reports or teaching material

The Custom “Peanut vs Donut” Dataset

To highlight differences between activation functions, a novel dataset was created:

Class 0 — Peanut Shape

Defined by a two-lobed radial function

Produces a curved, non-convex region

Class 1 — Donut Shape

A circular ring with slight perturbations

Encircles the peanut class completely

This structure cannot be separated by a linear model and therefore provides an excellent test for neural network nonlinearity.

All dataset generation code is included in the notebook.
Repository Structure
mlp-activations-tutorial/
LICENSE
README.md
Understanding MLP Functions Tutorial.pdf
mlp_fun_notebook.ipynb
peanut_donut_dataset.csv
How to Run the Notebook
1. Clone the repository
git clone https://github.com/Ram-sai7/MLP_Activation_Functions.git
cd mlp-activations-tutorial

2. Install dependencies
pip install numpy torch matplotlib scikit-learn

3. Launch Jupyter Notebook
jupyter notebook

Then open:

notebook/mlp_peanut_donut_with_figures.ipynb

4. Click “Run All”

The notebook will:

Generate the Peanut vs Donut dataset

Train MLP models with 4 activation functions

Export all figures into the figures/ folder automatically

Plot loss curves and decision boundaries

Exported Figures

This tutorial automatically saves four figures:

File Name	Description
fig_dataset.png	Visualisation of the Peanut vs Donut dataset
fig_activations.png	Comparison of activation functions
fig_training_loss.png	Training loss curves across activations
fig_decision_boundaries.png	4-way comparison of decision boundaries

You can directly include these figures in reports or presentations.

Accessibility Notes

To support inclusive learning:

A colour-blind-friendly palette (coolwarm) is used

Figures contain clear axis labels and readable titles

Alt-text descriptions are included in the PDF tutorial

Mathematical notation is compatible with screen readers

License

This project is released under the MIT License.
You may reuse, modify, or distribute this work, provided attribution is given.
