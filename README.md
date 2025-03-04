# Credit Card Fraud Detection with Variational Autoencoders

This project demonstrates the use of Variational Autoencoders (VAEs) for detecting credit card fraud. The notebook explores data preprocessing, feature scaling, and model training using both deep learning and traditional machine learning techniques.

## Dataset
The dataset used is a public credit card fraud detection dataset containing transactions made by European cardholders. It includes:
- **Features:** 30 columns including anonymized numerical features and a target column (`Class`).
- **Target:** Binary label indicating fraud (1) or non-fraud (0).

## Requirements
To run the notebook, you will need:
- Python 3.x
- Required libraries: `numpy`, `pandas`, `tensorflow`, `keras`, `scikit-learn`, `imblearn`, `seaborn`, `matplotlib`

Install the requirements using:
```
pip install -r requirements.txt
```

## Project Structure
- **Data Loading:** Loads and explores the dataset.
- **Preprocessing:** Handles class imbalance using oversampling and scales features.
- **Modeling:**
  - Variational Autoencoder for anomaly detection.
  - Random Forest Classifier for comparison.
- **Evaluation:** Uses ROC AUC and precision-recall metrics.

## Usage
Run the notebook cells sequentially to execute the workflow.

## Results
The notebook compares performance metrics between VAE and Random Forest models.

## License
This project is licensed under the MIT License.

