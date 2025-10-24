# ML Implementations

A collection of different ML Algorithms implemented by me.

## Table of Contents
- [Algorithms](#algorithms)
- [Getting Started](#getting-started)
- [License](#license)
## Algorithms
- [Linear Regression using Gradient Descent](#1-linear-regression-using-gradient-descent)
- [Multiple Linear Regression using Gradient Descent with Z Score Normalisation](#2-multiple-linear-regression-using-gradient-descent-with-z-score-normalisation)

    - ### 1. Linear Regression using Gradient Descent
        - Dataset used- ["Salary Dataset: Simple linear regression"](https://www.kaggle.com/datasets/abhishek14398/salary-dataset-simple-linear-regression)
        - View this [notebook](/notebooks/linearregression.ipynb) for the implementation.
        - Visualisation
        
        ![image](/assets/1_linearregression.gif)

    - ### 2. Multiple Linear Regression using Gradient Descent with Z Score Normalisation
        - Dataset used- ["Student Performance"](https://www.kaggle.com/datasets/nikhil7280/student-performance-multiple-linear-regression)
        - View this [notebook](/notebooks/multiplelinreg.ipynb) for the implementation.
        - Unlike the previous implementation, this time I divided my dataset into testing and training data and found my R^2 Score using the testing data while also comparing it with SkiKit.
        - Learning Curve for the 2 different alphas I took:

        ![image](/assets/2_linearregression1.png)
        - Actual vs Predicted Values Graph (for alpha=0.03):

        ![image](/assets/2_linearregression2.png)

## Getting Started

1. Clone the repository:
    ```bash
    git clone https://github.com/IndoRexian/ml-implementations.git
    cd ml-implementations
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. You can now play with various notebooks listed [here](/notebooks/).

## License

This project is licensed under the MIT License.