# Health Care Diabetes Logistic Regression

The **Health Care Diabetes Logistic Regression** project is a machine learning-based solution aimed at predicting the likelihood of diabetes in individuals based on various health-related features. Diabetes is a widespread chronic medical condition that affects millions of people globally. Early diagnosis and prediction of diabetes can significantly improve healthcare management and the quality of life for affected individuals. This project leverages logistic regression, a popular classification algorithm, to create a predictive model.

## Introduction

Diabetes is a metabolic disorder characterized by high blood sugar levels, which can lead to severe health complications if not managed properly. Timely identification of individuals at risk of diabetes is crucial for effective prevention and treatment. Logistic regression, a statistical method, can be employed to develop predictive models based on a set of input features.

## Dataset

The project utilizes a dataset that contains a variety of health-related attributes for a group of individuals. These attributes include:

- **Pregnancies**: The number of times a person has been pregnant.
- **Glucose**: Plasma glucose concentration measured in milligrams per deciliter (mg/dL).
- **BloodPressure**: Diastolic blood pressure measured in millimeters of mercury (mm Hg).
- **SkinThickness**: Triceps skinfold thickness measured in millimeters (mm).
- **Insulin**: 2-Hour serum insulin level measured in micro-units per milliliter (mu U/ml).
- **BMI (Body Mass Index)**: A measure of body weight adjusted for height (weight in kilograms / (height in meters)^2).
- **DiabetesPedigreeFunction**: A function that represents the genetic predisposition to diabetes.
- **Age**: The age of the individual in years.
- **Outcome**: A binary outcome variable, where 1 indicates the presence of diabetes, and 0 indicates the absence.

## Installation

To run this project, you'll need Python and the following libraries installed:

- NumPy
- Pandas
- scikit-learn


## Usage

The main script for this project is `diabetes_logistic_regression.py`. It performs the following steps:

1. Loads the dataset.
2. Preprocesses the data, handling missing values and scaling.
3. Divides the dataset into training and testing sets.
4. Builds and trains a logistic regression model.
5. Evaluates the model's performance using various metrics.
6. Provides insights into the predictive capabilities of the model.

To run the script, execute the following command:


Feel free to modify the script or experiment with different features to improve the model's accuracy and predictive power.

## Contributing

Contributions to this project are highly encouraged. If you have ideas for enhancements, bug fixes, or additional features, please open an issue or submit a pull request on the [GitHub repository](https://github.com/erenduyuk/Health-Care-Diabetes-Logistic-Regression).

## License

This project is open-source and is provided under the [MIT License](LICENSE). You are free to use and modify the code for your own purposes, subject to the terms of the license.

This project aims to contribute to the early detection and management of diabetes, ultimately improving the well-being of individuals at risk.


