# Machine-Learning-Project-Predicting-Titanic-Survival-with-Pipelines-and-Imputers

## Project Description

This project focuses on predicting the survival status of passengers aboard the Titanic using machine learning techniques. The goal is to build an accurate model by utilizing pipelines and various types of imputers for handling missing data. The project involves preprocessing the dataset, applying feature scaling, encoding categorical variables, and training a predictive model.

## Dataset

The project utilizes the Titanic dataset, which includes information about passengers such as age, fare, embarkation point, gender, and other attributes.

## Project Structure

The repository is structured as follows:

- `train.csv`: The dataset used for training and testing the model.
- `notebooks/`: Directory containing Jupyter Notebooks with step-by-step code implementation.
  - `1_data_preparation.ipynb`: Data loading, preprocessing, and feature engineering.
  - `2_model_training.ipynb`: Building the pipeline, including imputers, scalers, encoders, and the predictive model.
  - `3_model_evaluation.ipynb`: Evaluating the trained model and analyzing performance metrics.
- `README.md`: Overview of the project, including setup instructions and an explanation of the project structure.

## Instructions

To run the project and reproduce the results, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/pratik0502/titanic-prediction-pipelines.git
```

2. Navigate to the project directory:

```bash
cd titanic-prediction-pipelines
```

3. Install the required dependencies:

```bash
pip install -r requirements.txt
```

4. Explore the Jupyter Notebooks in the `notebooks/` directory to understand the project workflow and code implementation.

5. Execute each code cell in sequential order, following the instructions and comments provided.

## Results

The trained model achieved an accuracy score of 75% on the test set. The use of pipelines allowed for seamless data preprocessing, while employing different types of imputers enhanced the handling of missing values.

## Conclusion

This project demonstrates the effectiveness of using pipelines and various imputers in improving the accuracy of predictive models. The implementation showcased the importance of data preprocessing, feature scaling, categorical encoding, and hyperparameter tuning. Further enhancements can be explored by incorporating different models, additional feature engineering, or ensembling techniques.

Feel free to contribute to this project or customize it according to your needs!

