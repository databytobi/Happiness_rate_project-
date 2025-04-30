# Happiness_rate_project-
# Happiness Rate Prediction

This project aims to predict the perceived happiness rate (low or high) of a country's inhabitants based on two key factors: **life expectancy** and **long-term unemployment rate**. By leveraging machine learning techniques, this project provides insights into how these variables influence happiness perception.

---

## Overview

The project builds a classification model to predict happiness levels using:
- **Decision Tree Classifier**: A supervised learning algorithm for classification tasks.

The results are evaluated using performance metrics and visualized for better understanding.

---

## Libraries and Tools Used

The following Python libraries are used in this project:
- **Modeling and Metrics**:
  - `DecisionTreeClassifier`
  - `accuracy_score`
- **Data Manipulation**:
  - `pandas`
  - `numpy`
- **Visualization**:
  - `matplotlib`

---

## Features

- Load and preprocess data, including life expectancy and long-term unemployment rate.
- Train a **DecisionTreeClassifier** to classify perceived happiness into low or high categories.
- Evaluate the model using accuracy scores.
- Visualize data and results for deeper analysis.

---

## Installation

### Prerequisites

Ensure you have Python installed along with the required libraries. You can install the dependencies using the following command:

```bash
pip install -U scikit-learn pandas numpy matplotlib
```

---

## Usage

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/databytobi/happiness-rate.git
   ```
2. Run the script to train and evaluate the model:
   ```bash
   python main.py
   ```

---

## Evaluation Metrics

The project uses the following metric to evaluate the model:
- **Accuracy Score**: Measures how well the model predicts the happiness category.

---

## Project Structure

```
happiness-rate/
│
├── data/                  # Dataset files (if applicable)
├── notebooks/             # Jupyter notebooks for exploration and visualization
├── src/                   # Source code
│   ├── data_preprocessing.py
│   ├── model_training.py
│   └── evaluation.py
├── tests/                 # Unit tests
├── main.py                # Main script to run the project
├── README.md              # Project documentation
└── requirements.txt       # Python dependencies
```

---

## Contributing

Contributions are welcome! If you have ideas for improvements or additional features, feel free to submit a pull request or open an issue.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Scikit-learn, Pandas, NumPy, and Matplotlib for providing the tools to build and analyze the model.
