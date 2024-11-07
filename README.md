# Healthcare Cost Prediction using Machine Learning

## Project Overview

This project applies machine learning (ML) techniques to predict healthcare insurance costs, leveraging the *Medical Cost Personal Dataset*. By using various ML algorithms, including regression models, decision trees, random forests, support vector machines (SVMs), and neural networks, the project aims to improve the accuracy of healthcare cost predictions compared to traditional actuarial methods.

## Objective

The goal of this project is to evaluate the performance of different machine learning models in predicting health insurance costs and to identify key factors that influence these predictions. Additionally, the project addresses ethical considerations such as data privacy, algorithmic bias, and regulatory compliance.

## Key Features

- **Prediction Models**: Regression, decision trees, random forests, support vector machines (SVMs), and neural networks.
- **Feature Selection**: Recursive feature elimination, LASSO (Least Absolute Shrinkage and Selection Operator), and principal component analysis (PCA) to identify key factors affecting cost predictions.
- **Performance Metrics**: Mean squared error (MSE), mean absolute error (MAE), and root mean squared error (RMSE) for model evaluation.
- **Ethical Considerations**: Focus on ensuring data privacy, addressing algorithmic bias, and complying with regulations like HIPAA.

## Dataset

The project uses the **Medical Cost Personal Dataset**, which contains information about individuals' medical expenses based on personal data like age, sex, BMI, children, smoking habits, and region. This dataset is available on various open data platforms and is used to train and evaluate the prediction models.

### Dataset Features

- **Age**: Age of the individual
- **Sex**: Gender of the individual
- **BMI**: Body Mass Index (BMI)
- **Children**: Number of children/dependents covered by the insurance
- **Smoker**: Whether the individual smokes
- **Region**: Geographical region of the individual
- **Charges**: Medical cost for the individual (target variable)

## Installation

To run this project locally, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/bathulaveera2022/Healthcare Cost Prediction using Machine Learning.git
    cd healthcare-cost-prediction
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Load and preprocess the data from the `Medical_Cost_Personal.csv` file.
2. Train the model using the provided code for regression, decision trees, random forests, SVMs, and neural networks.
3. Evaluate the models using MSE, MAE, and RMSE metrics.
4. Identify the most significant features impacting the predictions using feature selection techniques.

## Ethical Considerations

- **Data Privacy**: Ensure that any sensitive data is handled responsibly and in accordance with privacy regulations like HIPAA.
- **Algorithmic Bias**: Address and mitigate any biases that may arise during model training to ensure fair predictions.
- **Regulatory Compliance**: Ensure that the models comply with healthcare regulations for ethical deployment in real-world applications.

## Contributing

Feel free to fork the repository, submit issues, or create pull requests to contribute to the project. We welcome any improvements or suggestions!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
