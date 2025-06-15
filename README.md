# Breast Cancer Prediction

A simple Machine Learning project that predicts the possibility of breast cancer using Logistic Regression.  
This project is implemented in a Google Colab and achieves an accuracy of **93%** on the test data.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Model](#model)
- [Results](#results)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [License](#license)
- [Contact](#contact)

---

## Overview

Early detection of breast cancer can significantly improve prognosis and survival rates.  
This project uses the Wisconsin Breast Cancer Dataset and leverages Logistic Regression to classify tumors as malignant or benign.

## Dataset

- **Source:** [Breast Cancer Wisconsin (Diagnostic) Data Set](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))
- **Features:** 30 numeric features computed from digitized images of fine needle aspirate (FNA) of breast masses.
- **Target Variable:** Diagnosis (`M` = Malignant, `B` = Benign)

## Model

- **Algorithm Used:** Logistic Regression
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-Score, Confusion Matrix

## Results

- **Accuracy achieved:** **93%**
- The model demonstrates strong performance in classifying between malignant and benign tumors.

## Getting Started

1. **Clone the repository:**
    ```bash
    git clone https://github.com/karthikeya-1303/Breast-Cancer-Prediction.git
    cd Breast-Cancer-Prediction
    ```

2. **Open the notebook:**
   - Use [Google Colab](https://colab.research.google.com/) (recommended) or Jupyter Notebook locally.

3. **Install dependencies (if running locally):**
    ```bash
    pip install pandas numpy scikit-learn matplotlib seaborn
    ```

## Usage

1. Open `Breast_Cancer_Detection.ipynb` in Jupyter Notebook or upload to Google Colab.
2. Run each cell in order to:
    - Load and explore the dataset
    - Visualize the data
    - Preprocess and split the data
    - Train the Logistic Regression model
    - Evaluate and interpret the results

## Project Structure

```
Breast-Cancer-Prediction/
├── Breast_Cancer_Detection.ipynb
├── README.md
```

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

Created by [karthikeya-1303](https://github.com/karthikeya-1303).  
For questions or suggestions, please open an issue.

---
