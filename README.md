# Polynomial Regression with Visualization

This project demonstrates how to perform polynomial regression using multiple approaches in Python. The goal is to fit a curve to generated data that follows a noisy polynomial pattern.

## What This Project Does

- Generates synthetic data points with a polynomial relationship and added randomness.
- Creates polynomial features up to a chosen degree.
- Trains polynomial regression models using:
  - **Normal Equation** (analytical method)
  - **Gradient Descent** (iterative method with optional standardization)
  - **Scikit-learn Pipeline** (using built-in tools for efficiency)
  - **Scikit-learn Manual** setup (explicit feature transformation and model fitting)

## What You’ll See in the Graphs

Each approach produces a plot:
- The **scatter points** show the noisy data.
- The **curve** shows how well the model has learned to fit the data.

All models use degree 3 polynomial features to capture the pattern in the data.

## Libraries Used

- `numpy` for data operations
- `matplotlib` for plotting
- `scikit-learn` for machine learning tools

## Why This Matters

This project provides a hands-on comparison between manual and built-in methods for polynomial regression. It helps understand both the math-driven and library-driven sides of machine learning in a visual way.

---

## How to Clone and Run This Project Locally

Open your terminal or command prompt and run the following commands:

```bash
# Clone the repository (replace the URL with the actual repo URL if hosted on GitHub)
git clone https://github.com/your-username/polynomial-regression-visualization.git
cd polynomial-regression-visualization

# (Optional) Create and activate a virtual environment
python -m venv venv
# On Windows:
venv\Scripts\activate
# On Mac/Linux:
source venv/bin/activate

# Install required packages
pip install numpy matplotlib scikit-learn

# Run the project script
python polynomial_regression.py