# Rock vs Mine Prediction Model
This repository contains a logistic regression model to predict whether sonar returns are from rocks or mines. The model is trained on a dataset that includes sonar frequency returns, which is useful in distinguishing between different types of objects underwater.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/ByteSlinger0307/Rock-Mine-Prediction_Model.git
    cd Rock-Mine-Prediction-Model
    ```

2. **Install the required dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## Dataset
The dataset used for this model consists of sonar returns collected for rock and mine objects. The data is loaded from a CSV file with no headers, implying that feature names are represented by column indices.

## Model
The model is a logistic regression classifier trained to differentiate between sonar returns from rocks and mines.

## Steps involved:

1) Data Loading: The dataset is loaded into a pandas DataFrame.
2) Exploratory Data Analysis (EDA): Statistical measures and value counts help understand the distribution of classes.
3) Data Splitting: The data is split into training and testing sets to evaluate the model's performance.
4) Training: The logistic regression model is trained on the training set.
5) Evaluation: Model performance is measured using accuracy on the test set.

## Usage
To run the model, use the provided Jupyter notebook or execute the script directly if provided. Ensure that the dataset is placed in the correct path as required by the script or notebook.

## Evaluation 
The model's performance is evaluated using the accuracy score, indicating how well it predicts rock vs. mine classifications.

## Contributors

- [Krish Dubey](https://github.com/ByteSlinger0307)

## Contact

- **Name**: Krish Dubey
- **Email**: [dubeykrish0208@gmail.com](mailto:dubeykrish0208@gmail.com)
- **GitHub**: [ByteSlinger0307](https://github.com/ByteSlinger0307)
- 
## License
This project is licensed under the MIT License.


