## Project Background

This academic group project was developed as part of the Master's program in Finance, Actuarial Science and Data Science at Université Abdelmalek Essaâdi, Morocco (2025–2026).

The project focuses on predicting customer churn using Machine Learning and Artificial Neural Networks, based on the Telco Customer Churn dataset.

## Project Contributors

- **Chaimae Moustaoui**
- **Ahlame El-Ghzaoui**
- **Imane Aklaa**

## Notebook Documentation

The Jupyter Notebook included in this repository was reconstructed from the Python implementation documented in our academic report.

Some technical adjustments were made to restore the executable workflow. The reconstructed notebook was subsequently tested in VS Code.

The original academic report and presentation document the methodology, results and conclusions of the group project.

## Project Files

- [Jupyter Notebook](notebooks/customer_churn_reconstructed_from_report.ipynb) — Python implementation of customer churn prediction using Machine Learning and Artificial Neural Networks.
- [Python Dependencies](requirements.txt) — Required libraries.

## How to Run

1. Download or clone this repository.
2. Install the Python dependencies:

```bash
python3 -m pip install -r requirements.txt
```

3. Open the notebook in VS Code or Jupyter.
4. Select a compatible Python environment and execute the cells in order.

**Note:** The notebook requires an internet connection to download the Telco Customer Churn dataset.

## Model Performance

The Artificial Neural Network was evaluated on a held-out test set of 1,407 observations.

| Metric | Result |
|---|---|
| Accuracy | 78.9% |
| ROC-AUC | 0.820 |
| Churn Precision | 64% |
| Churn Recall | 47% |
| Churn F1-score | 0.54 |

The model demonstrates useful discrimination between churn and non-churn customers. However, churn recall of 47% indicates that more than half of actual churn cases were missed at the selected classification threshold of 0.5. Improving recall is therefore an important area for future work.

*Results correspond to the saved notebook execution and may vary between training runs.*
