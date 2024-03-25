# Fruit Quality Prediction

## Description
This project aims to predict the quality of fruits using machine learning techniques. It utilizes various features such as color, size, texture, and other attributes to classify fruits into different quality categories.

## Features
- Dataset preprocessing: The dataset is preprocessed to handle missing values, encode categorical variables, and scale features as necessary.
- Machine learning models: Several machine learning models are implemented and evaluated for fruit quality prediction, including decision trees, random forests, support vector machines, and neural networks.
- Model evaluation: The performance of each model is evaluated using metrics such as accuracy, precision, recall, and F1-score to determine the most suitable model for fruit quality prediction.

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/nidhaahmed/Fruit-Quality-Prediction.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Fruit-Quality-Prediction
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Prepare the dataset: Ensure that the dataset containing information about fruits and their attributes is available.
2. Run the preprocessing script: Execute the preprocessing script to clean and preprocess the dataset.
    ```bash
    python preprocess.py
    ```
3. Train the models: Train machine learning models using the preprocessed dataset to predict fruit quality.
    ```bash
    python train.py
    ```
4. Evaluate model performance: Evaluate the trained models and analyze their performance using various metrics.
    ```bash
    python evaluate.py
    ```

## Contributors
- Nidha Ahmed Mohammad  [(link to my GitHub profile)](https://github.com/nidhaahmed)

## License
This project is licensed under the [MIT License](LICENSE).

## Additional Information
For more details about the project, refer to the [Jupyter Notebook](fruit-quality-prediction.ipynb) containing the code implementation and analysis.
