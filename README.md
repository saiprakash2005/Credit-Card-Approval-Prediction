
# Credit Card Approval System

This project utilizes machine learning techniques in Python to predict credit card approvals.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Models and Results](#models-and-results)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Introduction

The Credit Card Approval System is designed to automate the evaluation of credit card applications using machine learning algorithms. By analyzing historical application data, the system predicts whether a new application should be approved or rejected, streamlining the decision-making process for financial institutions.

## Dataset

The dataset used in this project is sourced from the UCI Machine Learning Repository and contains anonymized information about credit card applications. It includes various attributes such as age, income, employment status, and more. The dataset is included in this repository as `crx.data`.

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/abhinavsaurabh/Credit-Card-Approval-System.git
   cd Credit-Card-Approval-System
   ```

2. **Create a virtual environment (optional but recommended):**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install the required packages:**

   ```bash
   pip install -r requirements.txt
   ```

   *Note: Ensure that `requirements.txt` is present in the repository with all necessary dependencies listed.*

## Usage

After installation, you can explore the Jupyter notebooks provided to understand the data analysis and modeling process:

1. **Launch Jupyter Notebook:**

   ```bash
   jupyter notebook
   ```

2. **Open the notebook:**

   In the Jupyter interface, navigate to and open `Credit Prediction.ipynb`.

3. **Run the cells:**

   Execute the cells sequentially to preprocess the data, train models, and evaluate their performance.

## Models and Results

Several machine learning models were trained and evaluated for this project. The accuracy achieved by each model is as follows:

- **Decision Tree:** 84%
- **Logistic Regression:** 86.7%
- **Gradient Boosting Classifier:** 87.43%
- **AdaBoost Classifier:** 87.92%

These results indicate that ensemble methods like AdaBoost performed the best on this dataset.

## Contributing

Contributions are welcome! If you'd like to improve this project, please fork the repository, create a new branch, and submit a pull request. For major changes, open an issue first to discuss the proposed modifications.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgments

- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/credit+approval) for providing the dataset.
- [Medium article by Abhinav Saurabh](https://abhinavsaurabh.medium.com/credit-card-approval-system-using-machine-learning-cb27615b23ef) for insights and explanations related to this project.

