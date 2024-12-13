# Exploratory Factor Analysis Simulation Study

This repository contains information and materials related to a simulation study aimed at evaluating how **non-normal underlying distributions** impact the use of polychoric and tetrachoric correlations, and how these, in turn, affect the results of Exploratory Factor Analysis (EFA). Specifically, the study examines the recovery of factor loadings and the overall accuracy of EFA under this configuration.

## Contents

The simulation analysis workflow is documented in the `index.qmd` file and includes:

- **Design**: Details about the simulation conditions, including sample sizes, number of categories, underlying distributions, and factor structures.
- **Data Generation**: Scripts and methods for simulating datasets under normal and non-normal conditions.
- **Analysis**: Code for conducting EFA using Pearson correlations and polychoric/tetrachoric correlations, with a focus on categorical data.
- **Metrics**: Procedures for calculating bias, mean squared error (MSE), Tucker’s congruence coefficient, and other key performance metrics.
- **Visualizations**: Graphical outputs such as boxplots and contour plots to illustrate the results across simulation conditions.

## Work in Progress

This project is a **work in progress**, and the repository will be updated with additional analyses, improved visualizations, and refined documentation as the study evolves.

## License

This repository is shared under an open-source license. See the `LICENSE` file for details.
