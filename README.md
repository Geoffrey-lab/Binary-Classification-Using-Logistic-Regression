# Binary Classification Using Logistic Regression

This repository contains a Jupyter Notebook that demonstrates how to build a binary classification model using logistic regression. The objective is to predict whether a policyholder of an insurance product will file a claim within the upcoming year based on various features such as age, sex, BMI, steps, number of children, smoking status, region, and claim amount.

## Repository Overview

### Key Features

- **Introduction to Logistic Regression**: Understand the logistic function and how logistic regression transforms probability scores into classifications.
- **Data Loading and Exploration**: Load the insurance claims dataset and explore its structure and contents.
- **Data Preprocessing**: Prepare the data for modeling by transforming features, handling categorical variables using one-hot encoding, and splitting the dataset into training and test sets.
- **Model Training**: Train a logistic regression model using the processed dataset.
- **Model Evaluation**: Evaluate the model's performance and interpret the coefficients.
- **Advantages and Disadvantages**: Discuss the pros and cons of using logistic regression for binary classification.

### Dataset

The dataset used in this notebook is publicly available and can be accessed from the provided URL. It includes the following columns:
- `age`: Age of the policyholder.
- `sex`: Sex of the policyholder (male/female).
- `bmi`: Body mass index of the policyholder.
- `steps`: Number of steps taken by the policyholder.
- `children`: Number of children the policyholder has.
- `smoker`: Whether the policyholder is a smoker (yes/no).
- `region`: Geographic region of the policyholder.
- `insurance_claim`: Whether the policyholder has filed a claim (yes/no).
- `claim_amount`: Amount claimed by the policyholder.

### Dependencies

- Python 3.x
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- scikit-learn

### Notebook Contents

1. **Import Libraries**: Import necessary libraries and set up the environment.
2. **Load Data**: Load the insurance claims dataset and preview the data.
3. **Data Preprocessing**:
   - Separate features and labels.
   - Handle categorical variables using one-hot encoding.
   - Split the data into training and test sets.
4. **Model Training**:
   - Initialize and train a logistic regression model.
   - View the model's intercept and coefficients.
5. **Model Evaluation**:
   - Make predictions on the test set.
   - Interpret the model's coefficients to understand feature importance.
6. **Discussion**:
   - Advantages and disadvantages of logistic regression in binary classification tasks.

### Usage

To use this notebook, clone the repository and open the notebook in Jupyter. Follow the instructions in each cell to execute the code and observe the results. Adjust parameters as needed to explore different aspects of the dataset and logistic regression.

```bash
git clone https://github.com/your-username/logistic-regression-classification.git
cd logistic-regression-classification
jupyter notebook Logistic_Regression_Classification.ipynb
```

### Contributing

Contributions are welcome! If you have any suggestions or improvements, please create an issue or submit a pull request.
_______

### License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
