
# Sonar Signal Classification

## Project Overview
This project explores sonar signal classification using machine learning.

The repository contains a Jupyter Notebook for the project workflow and a CSV dataset for analysis.

## Repository Contents

- `Sonar_signal_classification.ipynb` — Jupyter Notebook containing the project code.
- `sonar_data.csv` — Dataset used in the project.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## How to Run

1. Clone or download this repository.
2. Install the required Python libraries.
3. Open `Sonar_signal_classification.ipynb` in Jupyter Notebook or Google Colab.
4. Run the notebook cells in order.


## Model Evaluation

The model was evaluated on a held-out test set of 42 samples.

| Metric | Test Result |
|---|---:|
| Accuracy | 92.86% |
| Macro F1-score | 0.93 |
| Weighted F1-score | 0.93 |

### Class-wise Results

| Class | Precision | Recall | F1-score |
|---|---:|---:|---:|
| 0 | 1.00 | 0.85 | 0.92 |
| 1 | 0.88 | 1.00 | 0.94 |

*Note: Results are from the current train/test split. Further validation is needed to assess generalization.*


The objective is to investigate how machine learning can be applied to sonar signal data for classification.

## Author

Adesh Gawande
