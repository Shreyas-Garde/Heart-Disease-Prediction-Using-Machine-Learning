# Heart Disease Prediction Using Machine Learning

Heart Disease Prediction is a Python-based machine learning project aimed at predicting the likelihood of heart disease in individuals. By leveraging a dataset in CSV format, the project trains and tests a machine learning model to make accurate predictions based on various health metrics and indicators.

## Features

- **Data Loading and Preprocessing**: Load and preprocess the heart disease dataset from a CSV file.
- **Feature Selection**: Select relevant features from the dataset to improve model performance.
- **Model Training**: Train the model using various machine learning algorithms such as logistic regression.
- **Model Evaluation**: Evaluate the model using performance metrics like accuracy and ROC-AUC.
- **Prediction**: Predict the likelihood of heart disease in new individuals based on their health metrics.

## Project Structure

- **heartdieseaspredictor.py**: The main Python program that handles data loading, preprocessing, model training, evaluation, and prediction.
- **requirements.txt**: A list of required Python modules for the project.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Shreyas-Garde/Heart-Disease-Prediction-Using-Machine-Learning.git
    cd Heart-Disease-Prediction-Using-Machine-Learning
    ```

2. Create a virtual environment:

    ```bash
    python -m venv venv
    ```

3. Activate the virtual environment:

    - On Windows:

        ```bash
        venv\Scripts\activate
        ```

    - On macOS and Linux:

        ```bash
        source venv/bin/activate
        ```

4. Install the required modules:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the main program:

    ```bash
    python heartdieseaspredictor.py
    ```

2. The script will:
    - Load and preprocess the dataset.
    - Split the data into training and testing sets.
    - Train the logistic regression model.
    - Evaluate the model using accuracy and ROC-AUC metrics.
    - Make predictions on new data.

## Modules Used

- `numpy`: For numerical computations.
- `pandas`: For data manipulation and analysis.
- `scikit-learn`: For machine learning algorithms and evaluation metrics.
- `matplotlib`: For data visualization.
- `seaborn`: For data visualization.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Author

**Shreyas Garde**

**GitHub Repository**: [Heart-Disease-Prediction-Using-Machine-Learning](https://github.com/Shreyas-Garde/Heart-Disease-Prediction-Using-Machine-Learning)

---

**Note**: Ensure you have the necessary configurations set up in `heartdieseaspredictor.py` for the project to work correctly.
