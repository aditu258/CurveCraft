# CurveCraft: Polynomial Regression

This project demonstrates the implementation of Polynomial Regression from scratch using Python, Scikit-learn, and Plotly. It explores how polynomial features can be used to fit a linear model to non-linear data. The repository includes a Jupyter Notebook (`polynomial-regression.ipynb`) that walks through the entire process, from data generation to model evaluation and visualization.

## How it Works

The project is divided into two main parts:

### 1. Polynomial Regression on 2D Data

-   **Data Generation**: We start by generating synthetic data that follows a quadratic equation: \(y = 0.8x^2 + 0.9x + 2\).
-   **Simple Linear Regression**: A simple linear regression model is first fitted to the data to show its limitations in capturing non-linear patterns.
-   **Polynomial Transformation**: `PolynomialFeatures` from Scikit-learn is used to transform the input features into polynomial features of a specified degree.
-   **Model Fitting**: A linear regression model is then trained on these transformed features.
-   **Evaluation**: The model's performance is evaluated using the R-squared (R²) metric, showing a significant improvement over the simple linear model.
-   **Visualization**: The results are visualized using Matplotlib, plotting the original data points and the fitted polynomial curve.

Here is a glimpse of the 3D polynomial regression plot:

![3D Polynomial Regression](https://github.com/aditu258/CurveCraft/blob/968a9070a6b2cc492f5aae3933ae6a96f7accf41/3D_Image.png)

### 2. Polynomial Regression on 3D Data

-   **Data Generation**: Synthetic 3D data is generated using the equation: \(z = x^2 + y^2 + 0.2x + 0.2y + 0.1xy + 2\).
-   **3D Visualization**: The generated data is visualized using Plotly's 3D scatter plot.
-   **Model Fitting**: A polynomial regression model is fitted to this 3D data.
-   **Surface Plotting**: The fitted model is visualized as a surface plot using Plotly, showing how the model captures the underlying structure of the data.

## How to Run

1.  Clone the repository:
    ```bash
    git clone https://github.com/your-username/CurveCraft.git
    ```
2.  Navigate to the project directory:
    ```bash
    cd CurveCraft
    ```
3.  Install the required dependencies:
    ```bash
    pip install numpy matplotlib scikit-learn pandas plotly
    ```
4.  Open and run the `polynomial-regression.ipynb` notebook in a Jupyter environment.

## Kaggle Notebook

You can find the original Kaggle notebook with the complete code and explanations here:
[Link to your Kaggle Notebook](https://www.kaggle.com/code/adityasinha07/polynomial-regression-from-scratch)

## Author

-   **Aditya Sinha**

---

_This README was generated with the help of an AI assistant._
