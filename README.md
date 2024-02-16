# Optimization-of-Standing-s-and-Glaso-s-Correlation-for-oil-formation-volume-factor

This repository contains a code step for optimizing parameters in a correlation equation used in the petroleum engineering field. The notebook uses optimization techniques to find the optimal parameters that minimize the mean squared error between the actual and predicted values of an oil formation volume factor (FVF) based on input parameters.

## Overview

The notebook consists of the following key components:

1. **Dataset**: The dataset used for optimization, containing input parameters (temperature, solution gas oil ratio, gas specific gravity, oil specific gravity) and corresponding oil formation volume factor (FVF) values.

2. **Optimization Methods**: The notebook implements various optimization methods to find the optimal parameters for the correlation equation. These methods include:
   - BFGS (Broyden–Fletcher–Goldfarb–Shanno) method
   - Nelder-Mead method
   - Conjugate Gradient (CG) method
   - Newton-CG method (requires Jacobian)

3. **Correlation Equation**: The correlation equation used for optimization is a standing's correlation equation or a similar equation commonly used in petroleum engineering to predict oil formation volume factors based on input parameters.

4. **Results**: The notebook outputs the optimized parameters for the correlation equation and calculates the mean squared error (MSE) between the actual and predicted FVF values using the optimized parameters.

## Usage

To use the optimization notebook:

1. Clone or download the repository to your local machine.
2. Install the required dependencies (`pandas`, `numpy`, `scikit-learn`, `scipy`).
3. Open the Jupyter Notebook (`optimization_notebook.ipynb`) using Jupyter Notebook or JupyterLab.
4. Run the notebook cells sequentially to load the dataset, perform optimization, and visualize the results.
5. Analyze the output to understand the optimized parameters and the accuracy of the correlation equation in predicting FVF values.

## Requirements

- Python 3.x
- Jupyter Notebook or JupyterLab
- Required libraries: `pandas`, `numpy`, `scikit-learn`, `scipy`

## License

This project is licensed under the [MIT License](LICENSE).

## Author

[Linkedin](www.linkedin.com/in/shedrach-igemhokhai) - [Email](shedrach.igemhokhai@gmail.com) 
