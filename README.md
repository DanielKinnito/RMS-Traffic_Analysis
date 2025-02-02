# Accident Severity Prediction

## Overview
This project focuses on predicting accident severity using machine learning techniques. The dataset undergoes various preprocessing steps, feature engineering, and model training using Random Forest and Gradient Boosting classifiers. Hyperparameter tuning is performed using GridSearchCV to find the best model.

## Project Structure
- `notebook.ipynb`: Jupyter Notebook containing the complete workflow of data preprocessing, model training, evaluation, and visualization.
- `notebook.txt`: Plain text version of the notebook, outlining the step-by-step process.

## Installation
To run this project, ensure you have Python installed along with the required dependencies.

```bash
pip install -r requirements.txt
```

## Dataset
The project utilizes an accident dataset (`Accident_Information.csv`) with up to 200,000 rows. The dataset includes various features related to accidents, which are processed for model training.

## Workflow
1. **Data Collection**: Load accident data from CSV.
2. **Data Preprocessing**: Handle missing values, remove unnecessary columns, and clean data.
3. **Feature Engineering**: Encode categorical variables and standardize numeric ones.
4. **Exploratory Data Analysis (EDA)**: Visualize distributions and correlations.
5. **Feature Selection**: Select top features using `SelectKBest`.
6. **Model Training**:
   - Train a `RandomForestClassifier`.
   - Train a `GradientBoostingClassifier`.
7. **Model Evaluation**:
   - Evaluate models using accuracy and classification reports.
   - Visualize feature importance.
8. **Hyperparameter Tuning**:
   - Use `GridSearchCV` to optimize the Gradient Boosting model.

## Running the Project
Run the Jupyter Notebook to execute the workflow step by step.

```bash
jupyter notebook notebook.ipynb
```

## Results
The project evaluates model performance through accuracy and classification reports. Feature importance analysis provides insights into the most significant variables affecting accident severity.

## Dependencies
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Ensure all dependencies are installed before running the project.

## Contributing
Contributions are welcome! Feel free to fork the repository and submit pull requests with improvements or additional features.
